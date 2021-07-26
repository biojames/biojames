
# Video encoding

## FFMPEG commands

### MOV > MP4 (Mac-compatible)

Compatible with Mac OSX playback and (as at mid-2021) provides higher quality Teams cloud-based video playback than libx265 and yuv444.

```bash
ffmpeg -i <input_file> -vcodec libx264 -crf 28 -pix_fmt yuv420p <output_file>
```
