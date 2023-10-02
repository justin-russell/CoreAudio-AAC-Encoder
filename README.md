# CoreAudio AAC Encoder for OBS

Ever wonder why your OBS stream's soundquality sounds bad? You likely are missing the `CoreAudioAACEncoder`
![image](https://github.com/justin-russell/iTunes-12.3.1.23/assets/38231076/59f468e4-59ad-4884-9079-094ca87efa0f)

The `CoreAudioAACENcoder` has *far* better sound quality than the default ffmpeg AAC encoder.

# How Do I Know If I Need It?
1. Open OBS
2. Click `Help`
3. Click `Log Files`
4. Click `View Current Log File`
5. Scroll up a bit and you should be able to find a log message that says: `[CoreAudio encoder]: CoreAudio AAC encoder not installed on the system or couldn't be loaded`
6. If you got the message above, then you need to install it. 

# Installation (Windows)
1. Download both `AppleApplicationSupport.msi` and `AppleApplicationSupport64.msi`
2. Double-click on each and run through the installer.
3. Once installed, you should be able to open OBS and it detect that you have `CoreAudioAACEncoder` installed by going to the current log file and seeing the message: `[CoreAudio encoder]: Adding CoreAudio AAC encoder`
4. That's it, you're now using it! Enjoy better audio quality for your live streams!

# Installation (Mac)
You shouldn't need to install it since it is builtin to MacOS

# Video On Installation
https://youtu.be/2TN06QO-Jqg
