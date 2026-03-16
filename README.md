# Klink — Discord Utility Bot

![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg?logo=python&logoColor=white)
![Discord.py](https://img.shields.io/badge/discord.py-2.3%2B-5865F2.svg?logo=discord&logoColor=white)
![License](https://img.shields.io/badge/license-GNU%20GPLv3-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen.svg)

A lightweight Discord bot written in Python that automatically detects and enhances links from GitHub and Twitter/X — fetching code snippets and re-embedding tweets with style and precision.

## Features

- **GitHub Line Snippets** → Detects GitHub links with line references (e.g., #L15 or #L10-L20) and returns syntax-highlighted snippets.
- **Twitter/X Post Enhancer** → Replaces default Discord embeds with custom blue embeds featuring author info, tweet text, replies, quotes, and media (videos prioritized).
- **Modular Design** → Organized into self-contained cogs for easy extension and maintenance.
- **Rate Limiting & Error Handling** → Prevents spam and gracefully handles API failures.
- **Multi-Line & Media Support** → Handles code ranges, images, videos, and quoted/replied tweets seamlessly.

## Inspiration

This project was inspired by and based on the concept of [Genesis](https://heliopolis.live/atums/genesis).
