# NI-ECUMC-XCP-DTO-Id

### Description ###
Some ECU might send the DAQ List data in CAN frames with ID different than the DTO_ID. Unfortunately, [NI ECUMC Toolkit readme](https://www.ni.com/pdf/manuals/377542j.htm#AdditionalProgrammingTopics) states that "XCP supports only DAQ that has a CAN identifier of DTO_ID".

This is a workaround library allowing NI ECUMC to support non-DTO_ID with DAQ for XCP_ON_CAN.

### Help ###
Examples are available in the example folder. The A2L file used in the example is not included due to confidentiality. 

### Source Version ###

LabVIEW 2019

### Source Dependencies ###

[NI ECU Measurement and Calibration Toolkit](https://www.ni.com/en-us/support/downloads/software-products/download.ecu-measurement-and-calibration-toolkit.html#445924)

### Known Issues ###


### Support and Contact ###
This add-on is provided as open-source software.  If it does not meet your exact specification, you are encouraged to modify the source code to meet your needs.  It is not officially supported by NI.

If you encounter a problem with this add-on, or if you have suggestions for a future revision, please submit a ticket in the [Issue](https://github.com/ZhiYang-Ong/NI-ECUMC-XCP-DTO-Id/issues) tab. Do not call NI for support for this add-on.


### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*
