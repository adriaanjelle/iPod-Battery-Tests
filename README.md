# iPod Battery Tests

Here, you can find some tests I've done for several of my iPods. This includes the iPod Classic (7th gen), Video (5.5th gen), and Mini (2nd gen).

**Some things you should know:**
- For the audio tests, I am using 256 Kb/s AAC songs, set to shuffle all of them. The screen will be off the entire time. I should note that the iPod Mini's screen stays on indefinitely (I found no way to change this behavior), but the backlight is off. In all tests, the audio is at maximum volume.
- For video, I have transcoded a 10-hour YouTube video of Epic Sax Guy[^1] at the lowest quality for H.264 using the Intel QSV encoder. The audio is at maximum volume, and the brightness is also set to the max.
- To find out the runtime, the audio output of the iPod is hooked up to a line-in on a computer which is recording all of it using Audacity. Once the battery dies, the waveform becomes a flat line and that decides the final runtime.
- The 'original' battery used in the 5.5th and 7th gen iPods are the same battery, which comes from a 7th gen iPod made in 2011 according to the date on the HDD.

## iPod Video (Enhanced)
| Serial No.  | Storage                                                 | Battery      | Software | Runtime |
|-------------|---------------------------------------------------------|--------------|----------|-----------------|
| 8M639N4CV9M | 30 GB HDD                                               | Original     | Original | Audio: 12h 16m<br>Video: 2h 27m                |
| 8M639N4CV9M | 30 GB HDD                                               | Original     | Rockbox  |                 |
| 8M639N4CV9M | Samsung Pro Plus 256 GB (2023), iFlash Quad             | Original     | Original | Audio: 14h 39m<br>Video: 2h 51m                |
| 8M639N4CV9M | Samsung Pro Plus 256 GB (2023), iFlash Quad             | Original     | Rockbox  |                 |
| 8M639N4CV9M | Samsung Pro Plus 256 GB (2023), iFlash Quad             | 1950 mAh[^2] | Original |                 |
| 8M639N4CV9M | Samsung Pro Plus 256 GB (2023), iFlash Quad             | 1950 mAh[^2] | Rockbox  |                 |

## iPod Classic
| Serial No.  | Storage                                                 | Battery      | Software | Runtime |
|-------------|---------------------------------------------------------|--------------|----------|-----------------|
| 8K227CQ09ZU | 160 GB HDD                                              | Original     | Original |                 |
| 8K227CQ09ZU | 160 GB HDD                                              | Original     | Rockbox  |                 |
| 8K227CQ09ZU | Samsung Pro Plus 512 GB (2023), iFlash Quad             | Original     | Original |                 |
| 8K227CQ09ZU | Samsung Pro Plus 512 GB (2023), iFlash Quad             | Original     | Rockbox  |                 |
| 8K227CQ09ZU | Samsung Pro Plus 512 GB (2023), iFlash Quad             | 1950 mAh[^2] | Original |                 |
| 8K227CQ09ZU | Samsung Pro Plus 512 GB (2023), iFlash Quad             | 1950 mAh[^2] | Rockbox  |                 |

## iPod Mini 2nd gen
| Serial No.  | Storage                                                 | Battery      | Software | Runtime |
|-------------|---------------------------------------------------------|--------------|----------|-----------------|
| JQ5360FQS42 | 6 GB HDD                                                | 750 mAh [^3] | Original | Audio: 24h 37m                |
| JQ5360FQS42 | 6 GB HDD                                                | 750 mAh [^3] | Rockbox  | Audio: 15h 28m                |
| JQ5360FQS42 | Samsung Pro Plus 256 GB (2023), iFlash SD to CF Adapter | 750 mAh [^3] | Original |                 |
| JQ5360FQS42 | Samsung Pro Plus 256 GB (2023), iFlash SD to CF Adapter | 750 mAh [^3] | Rockbox  |                 |

[^1]: [https://www.youtube.com/watch?v=ez8m4PXksQs](https://www.youtube.com/watch?v=ez8m4PXksQs)
[^2]: [https://www.aliexpress.com/item/1005004636235952.html](https://www.aliexpress.com/item/1005004636235952.html), listed as 365477, 1950 mAh.
[^3]: [https://www.123accu.nl/Apple-EC003-EC007-accu-750-mAh-123accu-huismerk-i10900.html](https://www.123accu.nl/Apple-EC003-EC007-accu-750-mAh-123accu-huismerk-i10900.html)
