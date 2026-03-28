VIDEO: https://www.youtube.com/watch?v=AW1yfBKRMKc&list=PLbIrFjvBZcv4_KD4_jN3f3OK1HfYh-Xit&index=22&t=32s
TIME: 00:46:54

ffmpeg -i input.mp4 -vf scale=960:-1 -movflags faststart -vcodec libx264 -crf 20 -g 1 -pix_fmt yuv420p output.mp4