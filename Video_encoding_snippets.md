
# Video encoding

## FFMPEG commands

### MOV > MP4 (Mac-compatible)

```bash
ffmpeg -i <input_file> -vcodec libx264 -crf 28 -pix_fmt yuv420p <output_file>
```
