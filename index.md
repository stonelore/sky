---
parse:
  file: "sky"
  # url: "https://necrologie.messaggeroveneto.gelocal.it/"
  url: "assets/sky.html"
  get: "#playinc table tr td:not(.boldblue):not([colspan]):nth-child(3)"
  # attribute: "alt"
  text: true
  update: "#playinc table tr:nth-of-type(3) td:nth-of-type(1)"
---
# Sky

{% include parse.html schema=page.parse %}
