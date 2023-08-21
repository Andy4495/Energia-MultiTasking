# Energia-MultiTasking Examples Library

[![Arduino Compile Sketches](https://github.com/Andy4495/Energia-MultiTasking/actions/workflows/arduino-compile-sketches.yml/badge.svg)](https://github.com/Andy4495/Energia-MultiTasking/actions/workflows/arduino-compile-sketches.yml)
[![Check Markdown Links](https://github.com/Andy4495/Energia-MultiTasking/actions/workflows/CheckMarkdownLinks.yml/badge.svg)](https://github.com/Andy4495/Energia-MultiTasking/actions/workflows/CheckMarkdownLinks.yml)

This repo is packaged as an Arduino library in order to access the MultiTasking examples that are included as part of the [Energia application][1]. It is not actually a library, but includes an `examples` folder so that Arduino will load the files and display the examples.

Energia includes several example sketches to demonstrate the multi-tasking functionality included in later releases of Energia (referred to as "EnergiaMT"). This functionality is based on [TI-RTOS][2].

Because these examples are included in the Energia application itself, they are not available when loading [Texas Instruments platform cores][5] into Arduino using the Boards Manager. I have therefore packaged them as a library so that they can be loaded into Arduino and be accessible through the `File->Examples->Energia-MultiTasking` menu.

## Installation

Download the Source code (zip) file from the Assets area of the [Releases][10] page. Then, from the Arduino IDE, select the `Sketch->Include Library->Add ZIP Library` menu to install the library.

## Usage

The example sketches are available from the `File->Examples->Energia-MultiTasking` menu.

## Documentation

The Energia website has an [overview][6] for using multi-tasking, and [tutorials][7] for several of the example sketches (scroll down to *8. MultiTasking*).

In case the Energia website goes offline, the overview and tutorial files are also available in the [`extras/docs`][8] directory in this repository. These files are also available in the [energia.nu][9] GitHub repo which contains the source files for the energia.nu website.

## License

Some of the files are copyright (c) Rei Vilo and licensed per [CC = BY SA NC][4].

For the other files/directories that do not mention a specific license, it is assumed that they are licensed per the Energia [license.txt file][3], in which libraries and cores are covered by the [GNU LGPL v2.1][102].

Please reference [`license.txt`][101] or the specific files for more details on the license.

[1]: https://energia.nu
[2]: https://www.ti.com/tool/TI-RTOS-MCU
[3]: https://github.com/energia/Energia/blob/master/license.txt
[4]: https://creativecommons.org/licenses/by-nc-sa/4.0/
[5]: https://github.com/Andy4495/TI_Platform_Cores_For_Arduino
[6]: https://energia.nu/guide/foundations/programming_technique/multitasking/
[7]: https://energia.nu/guide/
[8]: ./extras/docs/
[9]: https://github.com/energia/energia.nu
[10]: https://github.com/Andy4495/Energia-MultiTasking/releases
[101]: ./license.txt
[102]: https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html
[//]: # ([200]: https://github.com/Andy4495/Energia-MultiTasking)

[//]: # (This is a way to hack a comment in Markdown. This will not be displayed when rendered.)
