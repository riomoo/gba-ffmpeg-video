# GBA video conversion for ffmpeg + Meteo

## Instead of having to use an online converter
ffmpeg -i "input.ext" -c:v msmpeg4v2 -c:a adpcm_ms -g 15 -tune animation -crf 23 -b:a 96k -s 854x480 output.avi

## After this just use Meteo from here:
https://github.com/Sterophonick/mirror-meteo-avi2gba
