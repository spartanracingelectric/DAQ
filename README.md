# SRE Data Acquisition System
SRE Data Acquisition System (MoTeC L180 w/ T2 Telemetry) repo. For all DAQ related things not related to actual test data.

## Environment Setup
To get started, you will need to install:
- [MoTeC C185 Dash Manager](https://www.motec.com.au/c185/c185downloads/)
- [MoTeC i2 Standard](https://www.motec.com.au/i2/i2downloads/)
<br/>
The C185 Dash Manager software can be used to configure and get data from the MoTeC L180. The ```/configs``` folder of this repo holds the team's current logging configurations. The ```/dbc``` folder of this repo holds a collection of dbc files for each MoTeC CAN channel. As of SRE-5, the CAN0 bus is connected to CAN1 of the MoTeC. CAN2 of the MoTeC is used for MoTeC-specific logging sensors like the IMU.
<br/>
The i2 Standard software can be used to analyze the data (.ld files) pulled by the C185 Dash Manager.

## Where do I find actual test data?
[SRE Testing Google Drive](https://drive.google.com/drive/folders/1wOcILapplblPMH6SW1sONnLdDI6TsNsR?usp=sharing)