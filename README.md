# TPEG2
This repository contains TPEG2 Protobuf files.

## About TPEG2
![image](https://github.com/tisa-asbl/TPEG2/assets/17566892/e3c3e1a7-c18c-43c7-a3af-ae485a780b4e)

TPEG specifications offer a method for transmitting multimodal traffic and travel information, regardless of client type, location or required delivery channel (e.g. DAB, HD radio, Internet, DVB-x, DMB, GPRS, Wi-Fi …). Language independence has also been a prime principle in the design.

## How Does it work?
In contrast to TMC (event-based road traffic information), TPEGTM refers to a whole set or toolkit of specifications, for offering a wider range of services to a wider range of users and devices.
TPEGTM services are defined in a modular way and can therefore vary in a number of ‘directions’:

* Application – e.g. Road Traffic Messages, Public Transport Information or Parking Information. Each Application is uniquely identified by an Application ID ([AID](http://tisa.org/technologies/tpeg/tpeg-aid-table/)) that are allocated by the TPEG Application Working Group (([TAWG](http://tisa.org/activities/the-tpeg-applications-wg/))) of TISA.
* Transmission method – e.g. DAB digital radio, DMB, internet
* Location referencing method – e.g. table-based (using for example TMC location tables) or on-the-fly (using a method that gives a location reference that works with or without maps and does not require a look-up table to decode in the receiver)
* Device – e.g. intended for vehicle navigation systems, internet browsers or mobile devices
* Conditional Access – whether data is sent for free or only to users/devices who have somehow established the right to receive it, e.g. by paying a subscription. Encryption of TPEG data is possible by means of [Standardised Encryption Indicators](http://tisa.org/technologies/tpeg/tpeg-encryption-tables/) which are allocated by the TPEG Application Working Group ([TAWG](http://tisa.org/activities/the-tpeg-applications-wg/)) of TISA.

The term “profile” is used to define a combination of the above which, together, make up what you might think of as a single TPEGTM service. For example:

* displaying traffic incidents on a map graphic and supporting re-routing or route optimisation
* displaying public transport status information on a cell phone screen
 

### TPEG standards and recommendations for use
Check the [list](http://tisa.org/tpeg-standards-and-recommended-use/) of TPEG standards that have been published by ISO and TISA recommendation for implementation.

### TPEGTM Services today
TPEG is available in many countries around the globe. Any TPEG-service is uniquely identified worldwide by a [TPEG Service ID (TPEG SID)](http://tisa.org/about-tisa/services).

More information regarding the current status of deployment is available [here](http://tisa.org/technologies/tpegtm-services-map)
