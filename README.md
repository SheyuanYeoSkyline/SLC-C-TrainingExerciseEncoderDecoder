# Training Exercise Encoder/Decoder

## Description

* Create a connector that simulates and Encoder/Decoder.\
The following parameters must be displayed.

## Encoder

* Status
  * Read/Write
  * Enabled/Disabled
* Current Compressed Bitrate
  * Read
  * Unit: Mbps
  * Decimals: 3
* Auto Chroma Weight
  * Read/Write
  * Enabled/Disabled
* Chroma Weight
  * Read/Write
  * Unit: %
  * Range
* Lossless Mode
  * Read/Write
  * Enabled/Disabled

## Decoder

* Status
  * Read/Write
  * Enabled/Disabled
* Current Compressed Bitrate
  * Read
  * Unit: Mbps
  * Decimals: 3
* Progression Order
  * Read/Write
  * Options:
    * 0: LCRP
    * 1: RLCP
    * 2: RPCL
    * 3: PCRL
    * 4: CPRL
* Code Block Width
  * Read
  * Unit: px
* Code Block Height
  * Read
  * Unit: px

## Requirements

* Use default values to set initial values.
* Only the encoder or decoder can be enabled at one point in time.
* Once disabled display "Not Available" on the data parameters.
