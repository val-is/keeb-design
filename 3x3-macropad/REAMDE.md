# 3x3 Macropad + Encoder

this keeb is mainly intended to be used for art, but can obviously be used in a general purpose fashion

## constraints

the design should incorporate:
- QMK firmware
- 1x rotary encoder (EC11K1525413 or similar)
- 3x3 matrix of cherry MX profile swtiches
- uses atmega32u4
- has usb port (not usb-c)

reach goals +future revisions might include
- OLED screen
- hot-swappable switches
- bluetooth + battery

## BOM

```
caps (0805)
3x 0.1uF:   CC0805KRX7R9BB104   https://www.digikey.com/en/products/detail/samsung-electro-mechanics/CL21B104KBCNFNC/3890530
2x 22pF:    CL21C220JBANNNC     https://www.digikey.com/en/products/detail/samsung-electro-mechanics/CL21C220JB61PNC/3890691
1x 1uF:     CL21B105KBFNNNE     https://www.digikey.com/en/products/detail/samsung-electro-mechanics/CL21B105KAFNNNE/3889152
1x 10uF:    CL21A106KAYNNNE     https://www.digikey.com/en/products/detail/samsung-electro-mechanics/CL21A106KOQNNNG/5958083

diodes (SOD-123)
7x:         SM4007PL            https://www.digikey.com/en/products/detail/micro-commercial-co/1N4148W-TP/717311

fuse (3216)
1x:         nSMD050-24V         https://www.digikey.com/en/products/detail/bel-fuse-inc/0ZCJ0050AF2E/4156312

switches
7x:         ??                  https://mechanicalkeyboards.com/shop/index.php?l=product_detail&p=9462

keycaps
7x:         ??                  https://mechanicalkeyboards.com/shop/index.php?l=product_detail&p=3025

resistors (0805)
2x 22:      0805W8F220JT5E      https://www.digikey.com/en/products/detail/panasonic-electronic-components/ERJ-6GEYJ220V/87316
2x 10k:     0805W8F1002T5E      https://www.digikey.com/en/products/detail/panasonic-electronic-components/ERA-6AEB103V/1465971
3x 5k:      0805W8F5101T5E      https://www.digikey.com/en/products/detail/panasonic-electronic-components/ERJ-6GEYJ512V/46122

pushbutton
1x:         TS-1187A-B-A-B      https://www.digikey.com/en/products/detail/c-k/RS-187R05A2-DS-MT-RT/2747199

rotary encoder
1x ec11e:   EC11K1525413        https://www.digikey.com/en/products/detail/adafruit-industries-llc/5454/16583962
(this is SMD :/)

MCU
1x atm32u4: ATMEGA32U4-AU       https://www.digikey.com/en/products/detail/microchip-technology/ATMEGA32U4RC-AU/2507982

usb
1x:         0548190589          https://www.digikey.com/en/products/detail/molex-llc/0548190589/2421963

crystal
1x 16MHz:   CSTNE16M0VH3C000R0  https://www.digikey.com/en/products/detail/CX3225SB16000D0GZJC1/1253-1698-1-ND/5995245
```
