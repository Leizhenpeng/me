---
title: GitHub-Autotheme-Image-Readme
date: 2024-01-11T10:00:00Z
lang: en
duration: 2min
type: note
---

The original [GitHub proposal is here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to). It's rolled out basically everywhere on GitHub now.

## Solution One 

 ```
![Termux Logo](https://user-images.githubusercontent.com/72879799/153904003-d7dee710-6552-4d23-a803-7a9a0ba67d92.png#gh-dark-mode-only)
![Termux Logo](https://user-images.githubusercontent.com/72879799/153904095-9d78a019-8495-4035-8174-e3da8e4dd66b.png#gh-light-mode-only)
 ```

For example, [this repository](https://github.com/movie-web/movie-web/blob/dev/README.md?plain=1) uses this technique.

## Solution Two 

Directly use html picture tags to switch pictures according to the system theme

```
<a href="https://gitmaya.com" target="_blank" style="display: block" align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ConnectAI-E/GitMaya/assets/50035229/45cfd4f3-9c17-44d2-b6b7-3aa97c08006b" width="655" height="auto">
    <img alt="Active Contributors of ConnectAI-E/GitMaya - Last 28 days" src="https://github.com/ConnectAI-E/GitMaya/assets/50035229/1c28f0ca-d6e6-4ebd-b858-c4be3eff845e" width="655" height="auto">
  </picture>
</a>

```

This more like a hack, but it works. check outlook in [gitmaya](https://github.com/ConnectAI-E/GitMaya).
