# public

Reference: [Reddit Link](https://www.reddit.com/r/Ubiquiti/comments/1922vvz/change_chime_sound_on_poe_chime/)


| Description  | mp3                                | 
|-------------------|--------------------------------------------|
| Original          | sounds_sounds_ring_button_Chime.mp3                         | 
| Converted for POE chime          | chime.mp3                       | 

**Conversion command**

> sox original.mp3 chime.mp3 channels 1 speed 0.5

**Upload Command**

> curl -v -k https://chime-ip:8080/api/uploadRingtone/1/.mp3 -X POST -F file=@chime.mp3

