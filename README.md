# iPod Battery Tests

Here, you can find some tests I've done for several of my iPods. This includes the iPod Classic (7th gen), Video (5.5th gen), Photo (4th gen) and Mini (2nd gen).

**Some things you should know:**
- For the audio tests, I am using 256 Kb/s AAC songs, set to shuffle all of them. The screen will be off the entire time. I should note that the iPod Mini's screen stays on indefinitely (I found no way to change this behavior), but the backlight is off. In all tests, the audio is at maximum volume.
- For video, I have transcoded a 10-hour YouTube video of Epic Sax Guy[^1] at the lowest quality for H.264 using the Intel QSV encoder. The audio is at maximum volume, and the brightness is also set to the max.
- To find out the runtime, the audio output of the iPod is hooked up to a line-in on a computer which is recording all of it using Audacity. Once the battery dies, the waveform becomes a flat line and that decides the final runtime.
- The 'original' battery used in the 5.5th and 7th gen iPods are the same battery, which comes from a 7th gen iPod made in 2011 according to the date on the HDD. This battery is probably very degraded based on the runtimes compared to Apple's rated runtimes.

## iPod Photo
| Serial No.  | Storage                                                                                       | Battery      | Runtime | Runtime<br>(Rockbox) |
|-------------|-----------------------------------------------------------------------------------------------|--------------|---------|----------------------|
| 2Z6191PRTDS | 4 GB HDD[^4]<br>AliExpress IDE to CF adapter[^5]                                              | 1200 mAh[^7] |         |                      |
| 2Z6191PRTDS | Samsung Pro Plus 256 GB (2023)<br>iFlash SD to CF adapter<br>AliExpress IDE to CF adapter[^5] | 1200 mAh[^7] |         |                      |

## iPod Video (Enhanced)
| Serial No.  | Storage                                       | Battery      | Runtime                         | Runtime<br>(Rockbox) |
|-------------|-----------------------------------------------|--------------|---------------------------------|----------------------|
| 9C643LRFV9M | 30 GB HDD                                     | Original     | Audio: 12h 16m<br>Video: 2h 27m | 13h 47m              |
| 9C643LRFV9M | Samsung Pro Plus 256 GB (2023)<br>iFlash Quad | Original     | Audio: 14h 39m<br>Video: 2h 51m | 6h 54m               |
| 8M639N4CV9M | Samsung Pro Plus 256 GB (2023)<br>iFlash Quad | 1950 mAh[^2] | Audio: 40h 54m<br>Video: 7h 9m  | 20h 20m              |

## iPod Classic
| Serial No.  | Storage                                       | Battery      | Runtime                           | Runtime<br>(Rockbox) |
|-------------|-----------------------------------------------|--------------|-----------------------------------|----------------------|
| 8K143MC89ZU | 160 GB HDD                                    | Original     |                                   |                      |
| 8K143MC89ZU | Samsung Pro Plus 512 GB (2023)<br>iFlash Quad | Original     | Audio: 40h 23m |                      |
| 8K227CQ09ZU | Samsung Pro Plus 512 GB (2023)<br>iFlash Quad | 1950 mAh[^2] | Audio: 112h 15m<br>Video: 15h 30m | 27h 4m               |

## iPod Mini 2nd gen
| Serial No.  | Storage                                                                        | Battery      | Runtime | Runtime<br>(Rockbox) |
|-------------|--------------------------------------------------------------------------------|--------------|---------|----------------------|
| JQ5360FQS42 | 6 GB HDD                                                                       | 750 mAh [^3] | 24h 37m | 15h 28m              |
| JQ5360FQS42 | Samsung Pro Plus 256 GB (2023)<br>iFlash SD to CF Adapter                      | 750 mAh [^3] | 30h 22m | 10h 44m              |
| JQ5360FQS42 | Samsung Pro Plus 256 GB (2023)<br>AliExpress red SD to CF adapter[^6]          | 750 mAh [^3] |         |                      |
| JQ5360FQS42 | SanDisk Extreme 128 GB CompactFlash                                            | 750 mAh [^3] | 30h 33m | 13h 29m              |


[^1]: [https://www.youtube.com/watch?v=ez8m4PXksQs](https://www.youtube.com/watch?v=ez8m4PXksQs)
[^2]: [https://www.aliexpress.com/item/1005004636235952.html](https://www.aliexpress.com/item/1005004636235952.html), listed as 365477, 1950 mAh.
[^3]: [https://www.123accu.nl/Apple-EC003-EC007-accu-750-mAh-123accu-huismerk-i10900.html](https://www.123accu.nl/Apple-EC003-EC007-accu-750-mAh-123accu-huismerk-i10900.html)
[^4]: This HDD is from a 2nd gen Mini, the standard 20 GB HDD was dead when I got this iPod
[^5]: [https://www.aliexpress.com/item/1005004300246145.html](https://www.aliexpress.com/item/1005004300246145.html)
[^6]: [https://www.aliexpress.com/item/1005005648815081.html](https://www.aliexpress.com/item/1005005648815081.html)
[^7]: [https://www.123accu.nl/Apple-616-0183-accu-1200-mAh-123accu-huismerk-i10882.html](https://www.123accu.nl/Apple-616-0183-accu-1200-mAh-123accu-huismerk-i10882.html)
