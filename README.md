# PenguinData
## Introduction
|  |  |
|----|----|
| Data is this repository is from a project monitoring various metrics in a colony of Kororā near New Plymouth.  [The project, Finding Little Blue, is documented here](https://www.citscihub.nz/Finding_Little_Blue).<p>The data is gathered from sensors in and around Kororā burrows.  It is sent to an [IoT visulisation platform](https://cayenne.mydevices.com/).  The [MQTT protocol](https://mqtt.org/) is used to upload data and to keep a copy of the data on another platform that is uploaded here every hour. <p>The data above is a long-term archive.  Real-time data can be viewed using  links such as these:<br> [ZA 52](https://cayenne.mydevices.com/shared/600f70582130755bb21495b3), [Overview](https://cayenne.mydevices.com/shared/60bb14442a964b08bc381fcb), [Mound 2](https://cayenne.mydevices.com/shared/60bb14fd2a964b08bc38200e),  [Mound 3](https://cayenne.mydevices.com/shared/60bc37682a964b08bc39d0e4), [Mound 3 & 4 Nest Pair Compare](https://cayenne.mydevices.com/shared/60dadda627a49f08b6fb0c28) | ![Finding Little Blue logo](https://citscihub.s3.amazonaws.com/flb_logo.png)


## Data Structure
The filenames on that page are Cayenne device names (32 randomish characters) followed by the Cayenne channel number.
* 'Mouse over' a filename to see the Cayenne channel number on the right: ![Image showing channel number](Documentation/PenguinDataFiles.png)
* Click on a file name to download all the data for a channel.  This can be downloaded or copied and pasted into a spreadsheet.
* Click on a date and time and you can look at all the data uploaded over the hour leading up to that time.  
## Channel Numbers
| Ch | Mound | Nest | Unit   |
| -- | ----- | ---- | ------ |
| 1  |       |      |        |
| 2  |       | 14   |        |
| 3  |       | 9    |        |
| 4  |       | 8    |        |
| 5  | 2     |      | mVolts |
| 6  |       | 20   |        |
| 7  |       | 21   |        |
| 8  |       | 19   |        |
| 9  |       | 11   |        |
| 10 | 4     |      | mVolts |
| 11 |       | 7    |        |
| 12 |       | 6    |        |
| 13 |       | 5    |        |
| 14 |       | 4    |        |
| 15 | 1     |      | mVolts |
| 16 |       | 10   |        |
| 17 |       | 16   |        |
| 18 |       | 15   |        |
| 19 |       | 18   |        |
| 20 | 3     |      | mVolts |
| 23 |       |      |        |
