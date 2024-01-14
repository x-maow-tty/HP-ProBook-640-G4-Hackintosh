# Hackintosh
macOS 13.0 (Ventura) on HP ProBook 640 G4

Tested on:
- 13.6.3

## Disclaimer
**This EFI is not in a fully working nor stable state.**

There are large parts that are unfinished. It's not USB mapped, there is no battery readout, it lacks an RTC memory fix, etc.
Currently, this repository exists as a back-up while the install is further fleshed out.
Additionally, your hardware may differ in drastic ways. Some versions of this model include a dGPU which will never be supported by this EFI.

Use this mainly for educational purposes! You have been warned!

## Hardware
|Component       |Details                         |
|----------------|--------------------------------|
|Motherboard     |HP 83D2                         |
|CPU             |Intel Core i5-8350U             |
|Memory          |2x 8GB DDR4                     |
|Storage         |ADATA SU800NS38                 |
|iGPU            |Intel UHD Graphics 620          |
|Wireless Adapter|Intel Dual Band Wireless-AC 8265|
|Audio Codec     |Conexant CX8200                 |

## Installation
Tips:
- If you don't know how to set up a Hackintosh, you shouldn't be using this. [Dortania's Install Guide](https://dortania.github.io/OpenCore-Install-Guide)
- `PlatformInfo` fields have been stripped for potential security reasons.