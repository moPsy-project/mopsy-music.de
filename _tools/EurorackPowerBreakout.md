---
layout: tool
nav: tools
name: Eurorack Power Breakout
short: Eurorack Power on the Breadboard
outline: EurorackPowerBreakout/outline.png
picture: EurorackPowerBreakout/breadboard-shot.png
documentation:
  github: https://github.com/moPsy-project/eurorack-power-breakout
  others:
    - label: User Manual v1.2
      url: https://github.com/moPsy-project/eurorack-power-breakout/releases/download/v1.2/Eurorack_Power_Breakout_User_Manual_v1_2.pdf
    - label: User Manual v1.1
      url: https://github.com/moPsy-project/eurorack-power-breakout/releases/download/v1.1/Eurorack_Power_Breakout_User_Manual_v1_1.pdf
availability:
  # Lifecycles: concept, dev, prod, discontinued
  lifecycle: prod
  shops:
  - label: Assembled Board on Etsy
    url: https://www.etsy.com/de-en/listing/1505680672/eurorack-power-supply-breakout
dimensions:
  height: 54 mm
  width: 22 mm
current:
  V12p: 1.2 mA
  V12n: 1.2 mA
  V5: 0.5 mA

---
This is a breakout board to provide a filtered power supply from the Eurorack Bus to your breadboard.

A bus decoupling setup like this would typically be found on your module.

The top rail can be switched between +5V or ground, depending on your prototype's needs.

The CV and Gate signals from the bus are available on the breakout board, in case your build uses them.

Please note: This requires a Eurorack Synthesizer power bus, as a Eurorack module would.
