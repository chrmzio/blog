# Wallpapers Directory

This directory is for your custom video wallpapers.

## Usage

1. Add your video files (MP4 format recommended) to this directory
2. Update your blog's config.toml to reference the video:

```toml
[theme]
  video_background = "your-video.mp4"
```

## Notes

- If no video_background is specified, a cyberpunk CSS gradient will be used
- Video files should be optimized for web (compressed, reasonable file size)
- Supported formats: MP4 (recommended), WebM
- For best performance, keep videos under 10MB

## Example

To use the default cyberpunk smoking video:
1. Download it from the bib repository
2. Place it in this directory as "cyberpunk-smoking.mp4"
3. Set video_background = "cyberpunk-smoking.mp4" in config.toml
