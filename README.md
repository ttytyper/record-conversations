# Record conversations

Records periods of audio to timestamped files. Silence is trimmed and a long
period of silence triggers the end of one recording and the beginning of the
next. This could be used for e.g. keeping an audio log of walkie-talkie or
amateur radio chatter, with one conversation per audio file. Audio is
recorded to ogg files for easy meta tagging.

Any parameters to the script are added as arguments to rec(1). In particular
this can be used to select your audio source. You could also apply a band
pass filter and normalization:

```record-conversations sinc 200-4500 norm```
