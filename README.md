# Make ReadWrite (mkarw) #



### What is this ? ###

Since the releaes of Android 10, all (or at least most) phones are released with dynamic parititons, which is pretty straightforward, dynamic partitioning so OEMs can resize / add / delete partitions as their will. In current stages, most of the OEM images are still read-only as unpacked in firmware extractors. Modifying them directly with traditional methods (editing in MT manager / other root explorers) will cause phone not to boot / boot to bootloader in most cases. After some research, it is found that dynamic parititons and the read-only file system is causing such issues. This Zip, makes the partitions Read-write and therefore allows modification towards the partitions. 

### Why is this ? ###

This is made possible by ```blockdev```. 

You can run the commands manually, but most people are lazy like me so I made a zip :p 

### Currently supported partitions ###

```system``` ```vendor``` ```product``` ```system_ext``` ```system_a``` ```system_b``` ```vendor_a``` ```vendor_b``` ```product_a``` ```product_b```

### Proof of the zip working ###

The zip has been tested on my device, curtana.

### Credits ###

 [phhusson](https://github.com/phhusson) - Inspiration of this zip
 
 [henloboi](https://github.com/JamieHoSzeYui) - Creator of ZIP
 
### Downloads ###

Move to "releases" tab, find mkarw release.



