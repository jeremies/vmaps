# vmaps

## Generar letra en videos

ffmpeg -i midroll-2s.mp4 -vf "drawtext=text='B':fontcolor=black:fontsize=200:x=100:y=100" -c:a copy midroll-2s-B.mp4

## Recortar videos

ffmpeg -i midroll.mp4 -ss 00:08 -to 00:10 -c copy midroll-2s.mp4
