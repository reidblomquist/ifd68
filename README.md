# Motivation
The keywalker IFD68 keyboard is a pretty fine 68 keys keyboard with backlight and wireless connectivity. Unfortunately, documentation and support seems scarce at best. This repo will try to dive deep into the capabilities and findings associated with this board.

Also, the board documentation points to the domain 'keywalker.cn', but unfortunately, the DNS for that domain is empty as of August 2017, so no chance of getting official support right now.

# Board Details

| Attribute | Value |
| --------- | ----- |
| Name | Keywalker IFD68 |
| Layout | 68 Keys |
| Connectivity | USB + Bluetooth |
| Battery | Polymer lithium 3.7V 1200 mAh 4.44 Wh |
| Programmable | Yes |
| Led backlight | Yes, white LEDs |
| Dimensions | 316.5 * 109 * 35.5 (mm) |
| Controller | [STM32F103CB](http://www.st.com/content/st_com/en/products/microcontrollers/stm32-32-bit-arm-cortex-mcus/stm32-mainstream-mcus/stm32f1-series/stm32f103/stm32f103cb.html) [UNCONFIRMED] |
| Images | [Pictures](https://github.com/GonzaloAlvarez/ifd68/tree/master/media) |

# Board Default Config

## Key composite

| Key pressed |  Function |
| ----------- | --------- |
| Fn + [1-9,0,+,++] | F1-F12 |
| Fn + [ / Fn + ] | Home / End |
| Fn + P | Print |
| Fn + Win Win | Lock |

Keys behavior can be personalized (and resetted) using the [official programmer](https://github.com/GonzaloAlvarez/ifd68/tree/master/software/original/programmer)

## Lights

| Key pressed |  Function |
| ----------- | --------- |
| Fn + \ | Light effect switch |
| Fn + Up/Down | Increase/Decrease brightness |
| Fn + Esc | All lights on (effects off) |
| Fn + Space | Stop running effect |

See more in the [User manual](https://github.com/GonzaloAlvarez/ifd68/blob/master/media/docs/IFD68-User-Manual.pdf)

## Bluetooth pairing
| Key pressed |  Function |
| ----------- | --------- |
| Long press Fn + Q/W/E | Enter bluetooth matching |
| Short press Fn + Q/W/E | Reconnect bluetooth |

See more in the [User manual](https://github.com/GonzaloAlvarez/ifd68/blob/master/media/docs/IFD68-User-Manual.pdf)

# External resources

* [Massdrop product page](https://www.massdrop.com/buy/keywalker-68-bluetooth-mechanical-keyboard)
* [TaoBao product page](https://item.taobao.com/item.htm?spm=a230r.1.14.43.73b217c4Z58Gq4&id=553191491984)
* [Pinwaishe product review](http://www.pinwaishe.com/wspc/19828.html)
* [SpritesModes hacking a keyboard](https://spritesmods.com/?art=rapidisnake)
* [FCC Compliance Tests](https://fccid.io/2AMOT-IFD-68)
