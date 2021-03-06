sublime-hl7-syntax
==================

Sublime Text Versions 2 & 3 syntax highlighting for HL7 content.

![hl7.png](hl7.png)

Most commonly used HL7 message types include: 
* ACK – General acknowledgement
* ADT – Admit, Discharge, Transfer
* BAR – Add/change billing account
* DFT – Detailed financial transaction
* MDM – Medical document management
* MFN – Master files notification
* ORM – Order (Pharmacy/treatment)
* ORU – Observation result (unsolicited)
* QRY – Query, original mode
* RAS – Pharmacy/treatment administration
* RDE – Pharmacy/treatment encoded order
* RGV – Pharmacy/treatment give
* SIU – Scheduling information unsolicited

Corepoint link below.

## Installation Options

#### Manual install MacOS

Sublime Text 2:

```
git clone https://github.com/cjohnson496/HL7-Syntax-Highlighting \
~/Library/Application\ Support/Sublime\ Text\ 2/Packages/sublime-hl7-syntax
```

Sublime Text 3:

```
git clone https://github.com/cjohnson496/HL7-Syntax-Highlighting \
~/Library/Application\ Support/Sublime\ Text\ 3/Packages/sublime-hl7-syntax
```

#### Package Control

First, install the Package Control plugin, instructions here: https://packagecontrol.io/installation.

Once you install Package Control, restart Sublime Text and bring up the Command Palette (<kbd>command+shift+p</kbd> on OS X, <kbd>super+shift+p</kbd> on Linux/Windows).

Select "Package Control: Install Package", wait while Package Control fetches the latest package list, then select "HL7 Redux" when the list appears.

## Usage

File types ending in `.edi` or `.hl7` should automatically have syntax highlighting applied, if not use the following commands to set syntax to HL7:
- Linux: <kbd>super+shift+p</kbd>, then type <kbd>ss hl7</kbd>
- Windows: <kbd>super+shift+p</kbd>, then type <kbd>ss hl7</kbd>
- OS X: <kbd>command+shift+p</kbd>, then type <kbd>ss hl7</kbd>

##  Disclaimer
> THIS CODE IS PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.

## Info / Reference

#### Sublime Text
- http://www.sublimetext.com

#### HL7 
- https://corepointhealth.com/resource-center/hl7-resources
