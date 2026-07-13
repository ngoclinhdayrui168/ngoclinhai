# NgocLinh AI Video Template

This repository contains programmatic video templates built with [Remotion](https://www.remotion.dev/), designed for creating educational content for TikTok, YouTube Shorts, and Reels.

## Author
**Ngoc Linh**

## Features
- **Code-driven animation**: Videos are generated using React and TypeScript.
- **Tailwind CSS**: Styled for rapid and consistent design.
- **TikTok/Shorts Optimized**: 9:16 aspect ratio (1080x1920) with "Safe Zone" padding.
- **Components**: Reusable slides for educational technical content.

## Compositions included
1. **LinuxFileSystem**: A 50s vertical video explaining the Linux Directory Structure.
2. **DockerIntro**: A vertical video introducing Docker concepts.

## Installation

```bash
git clone https://github.com/ngoclinhdayrui168/ngoclinhai.git
cd ngoclinhai
npm install
```

## Usage

Start Preview Studio:

```bash
npm run dev
```

Render video:

```bash
npx remotion render LinuxFileSystem
npx remotion render DockerIntro
```

## License
Licensed under the MIT License.
