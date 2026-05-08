# x-meme

Programmatic MV & meme video generation powered by [HyperFrames](https://hyperframes.heygen.com).

## Quick Start

```bash
# Preview in browser (live reload)
pnpm run dev

# Validate composition
pnpm run check

# Render to MP4
pnpm run render
```

## Tech Stack

- **Framework**: [HyperFrames](https://hyperframes.heygen.com) (HTML-native video rendering)
- **Animation**: [GSAP](https://gsap.com) (timeline-based animation)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com) (browser runtime)
- **Rendering**: Headless Chrome → FFmpeg → MP4

## Requirements

- Node.js >= 22
- FFmpeg