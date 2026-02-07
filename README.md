# Liquid Glass MP3 Visual Player

A browser-based MP3 visual player with a centered rotating disc, circular colorful music spectrum lines, and an Apple-inspired Liquid Glass control panel.

中文文档: [README.zh-CN.md](README.zh-CN.md)

## Features

- Centered circular MP3 disc with continuous 360° rotation
- Circular colorful spectrum lines around the disc
- Apple-style Liquid Glass UI controls
- Select local MP3 and loop playback
- Select custom background image
- Select custom music icon image (disc artwork)
- Disc opacity slider
- `Config Complete` workflow before playback
- `Start` / `Pause` playback controls
- Hide/show control panel controls
- Built-in bilingual UI switch (`中文` / `English`)

## Project Structure

```text
.
├─ html/
│  └─ HTML-MusicPlayer-Zh-cn.html
├─ README.md
└─ README.zh-CN.md
```

## Quick Start

1. Clone this repository.
2. Open `html/ball.html` in your browser.
3. Recommended browsers: Chrome / Edge (latest).

No build tools or dependencies are required.

## Usage

1. Click `Select MP3` / `选择 MP3` and pick a local `.mp3` file.
2. Optional setup:
- `Select Background` / `选择背景图`
- `Select Icon` / `选择音乐图标`
- Adjust `Icon Opacity` / `图标透明度`
3. Click `Config Complete` / `配置完成`.
4. Click `Start` / `开始` to play, or `Pause` / `暂停`.
5. Use `Hide Panel` / `隐藏控制面板` and `Show Panel` / `显示控制面板` when needed.
6. Use `Language` button to switch between Chinese and English UI.

## Notes

- Browsers may require one user interaction before audio playback is allowed.
- Local files are loaded via `ObjectURL` and remain local to the browser session.
- Circular spectrum lines animate continuously and react to audio when playing.

## License

Add your preferred license (for example, MIT).

