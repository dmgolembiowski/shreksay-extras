# Rebuilding WAV files for programmatic slicing

> Joining the tarball paritions

```sh
   cat Shrek_1.wav.tar.gz.part* > Shrek_1.wav.tar.gz \
&& cat Shrek_2.wav.tar.gz.part* > Shrek_2.wav.tar.gz \
&& cat Shrek_3.wav.tar.gz.part* > Shrek_3.wav.tar.gz
```

> Un-tarring the audio you need

```sh
tar xvfz Shrek_1.wav.tar.gz
```


