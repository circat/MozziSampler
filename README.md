# MozziSampler
Wavetable Wample Player based on the Mozzi Library by Tim Barrass

WORKAROUND :

1. Convert WAV file with Audacity to RAW,8 bit signed WAV (.raw)
2. convert RAW Wace with char2mozzi.py by command promt in folder of wave+.py file,enter :
   char2mozzi.py wavefilename.raw wavefilename.h TABLENAME LENGTH
for example my Bjork - Vocalsample : char2mozzi.py bjork.raw bjork.h bjable 16384
3. Open the created ".h" file and copy the Table , lenght and Name to your Arduino Script

