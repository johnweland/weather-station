# Weather Station
Because I don't have a more creative name for it.

## The Idea
The idea is not novel; create a DIY weather station using a micro controller some sensors and a 3D printed housing. The difference however is that once it is working. It should work completely off grid and the data should be parsed in to JSON or some other notation and transmitted over LoRa. So the weather station could be set in a backyard, community garden, or out in the middle of a field and not require any utilities within a few kilometers. 

I have made up my mind on what sort of data I would like to collect to start and have already purchased, or built most of the parts. I am open to suggestions on what other types of data would be handy to have. (seismic data perhaps)

## Sensors & Useage
| Decided | Sensor                                            | Use Case                        |
|  :---:  | :---                                              | :---                            |
|    ✔    | [BME280](https://www.adafruit.com/product/2652)   | Temperature, Humidity, Pressure |
|    ✔    | [LTR390](https://www.adafruit.com/product/4831)   | Light, UV Index                 |
|    ✔    | [US5881LUA](https://www.adafruit.com/product/158) | Wind Speed                      |
|    ?    | []()                                              | Wind Direction                  |
|    ✔    | [PMSA003I](https://www.adafruit.com/product/4632) | Air Qualiy                      |
|    ✔    | [US5881LUA](https://www.adafruit.com/product/158) | Rain Gauge                      |
|    ✔    | [FeatherS3](https://esp32s3.com/feathers3.html)   | Micro Controller                |


