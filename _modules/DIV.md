---
layout: module
nav: modules
name: DIV
short: Simple clock divider, similar to the Doepfer A-160-1.
panel: DIV/frontpanel.png
picture: DIV/div-case-shot-frame.png
width: 4
documentation:
  github: https://github.com/moPsy-project/div
  modulargrid: https://www.modulargrid.net/e/other-unknown-mopsy-div
  others:
    - label: User Manual v1.1
      url: https://github.com/moPsy-project/div/releases/download/v1.1/DIV_User_Manual.pdf
    - label: Assembly Guide v1.1
      url: https://github.com/moPsy-project/div/releases/download/v1.1/DIV_v1.1_Assembly_Guide.pdf
availability:
  # Lifecycles: concept, dev, prod, discontinued
  lifecycle: prod
  shops:
  - label: Assembled Module on Etsy
    url: https://www.etsy.com/de-en/listing/1496940825/mopsy-div-eurorack-modul
dimensions:
  width: 4 HP
  depth: 40 mm
current:
  V12p: 40 mA
  V12n: --
  V5: --

---
This module works as a rhythm and clock divider, as expected, but also accepts audio frequencies and happily scales your waves down by several octaves (bear in mind that the output will be 50% PWM).

The reset input can be configured for triggers from the bus gate.
