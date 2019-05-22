# Arduino Fingerprint Sensor With Lock
### Using one of these two fingerprint readers is easy with an Arduino

### LCSC - More Asian Brands, Lower Prices, 4 Hours Ready for Shipping  
#### China's leading Electronics Components source - 113 Authorized Brands, 174 International Brands, 555 Made in Asia Brands  
#### LCSC has been confirmed by ISO 9001: 2015.  
#### Shop: https://lcsc.com/

I' ujsing two different (but very similar) fingerprint readers here, an R307 and a slightly different, Adafruit-compatible version. I show here how to enrol fingerprints using the Windows (only) demo program and then read them back on the Arduino to power a small door lock.

You can do everything on the Arduino, of course, but it makes sense to use the Windows' utility IDE first to ensure it all hangs together. I show you how to do this, all very easy once you have chosen a _suitable Arduino UNO to use._

#### Suitable Arduino Uno?
My original attempts at getting my R307 fingerprint reader working (over two years ago) came to nothing. Now, thanks to some comments in the Adafruit article I figured I needed an Arduino UNO with a "proper" USB to Serial converter, such as the µController found on the original Arduino Uno (an ATMega16U2). Luckily, I had an old, possibly cloned version of that board and it all sprang into life, so very easily!

I didn't amend the Adafruit demo sketch for the Arduino to read the fingerprints, other than to power up the door lock if it found a matching fingerprint. There are dozens of different, 12v door locks out there - check what you need and how to fix it before buying one! Also, bear in mind that these locks take quite some current (the small one I used needs just under 400mA).











### LINKS







, both available from Banggood and AliExpress. The Adafruit one is currently out of stock (May 2019) but will doubtless return.
