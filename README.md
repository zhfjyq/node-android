# node-android
node for android platform.
you can using it for standalone mode or embedded mode.
cur version 7.9.0

# standalone mode
* using for root android version
* you can run node application in shell,or in init.rc
## prebuilding version
* you can using prebuilding node in you android device
* using 'adb push' command push /bin/node to you device
* then using 'adb shell chmod 755' command give execute permission to you pushed node
* NOTE: dont push node to '/sdcard' directory, because it can't set execute.



# embedded mode
* you can embedded node in you android java application
* NOT need ROOT device,it like a normal app


# Thanks for dna2oslab
* NODEJS For Android Compile Refrenced dna2oslab:
* https://github.com/dna2github/dna2oslab/tree/master/android
