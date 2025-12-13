# Tarokina Language Packs

Remote language packs for the [Tarokina Pro](https://tarokina.com) WordPress plugin.

## How It Works

The Tarokina plugin automatically downloads translation packs from this repository when users change their WordPress language setting. No manual installation required.

## Available Languages (6)

| Flag | Language | Locale | Size | Link |
|:----:|----------|--------|-----:|------|
| 🇹🇼 | Chinese Traditional (Taiwan) | `zh_TW` | 160.8 KB | [Download](https://github.com/fernandopro/tarokina-languages/releases/download/v3.0.3/tarokina-lang-zh_TW.zip) |
| 🇫🇷 | French (France) | `fr_FR` | 159.6 KB | [Download](https://github.com/fernandopro/tarokina-languages/releases/download/v3.0.3/tarokina-lang-fr_FR.zip) |
| 🇩🇪 | German (Germany) | `de_DE` | 161.2 KB | [Download](https://github.com/fernandopro/tarokina-languages/releases/download/v3.0.3/tarokina-lang-de_DE.zip) |
| 🇮🇹 | Italian (Italy) | `it_IT` | 156.5 KB | [Download](https://github.com/fernandopro/tarokina-languages/releases/download/v3.0.3/tarokina-lang-it_IT.zip) |
| 🇯🇵 | Japanese | `ja` | 168.1 KB | [Download](https://github.com/fernandopro/tarokina-languages/releases/download/v3.0.3/tarokina-lang-ja.zip) |
| 🇪🇸 | Spanish (Spain) | `es_ES` | 156.2 KB | [Download](https://github.com/fernandopro/tarokina-languages/releases/download/v3.0.3/tarokina-lang-es_ES.zip) |

## Current Version

**v3.0.3** - Compatible with Tarokina Pro v3.0.3

## Installation

Language packs are installed **automatically** by the Tarokina plugin:

1. Install and activate Tarokina Pro
2. Go to **Settings → General → Site Language**
3. Select your preferred language
4. Tarokina will download the translation automatically

## For Developers

### Adding a New Language

1. Generate translation using OpenAI script
2. Package with `npm run package-lang`
3. Upload with `npm run upload-lang`

See [Remote Languages Documentation](https://github.com/fernandopro/tarokina-2025/tree/main/docs/addons/remote-languages) for details.

### Repository Structure

```
releases/
└── v3.0.3/
    ├── tarokina-lang-{locale}.zip
    └── ...
```

## License

These translations are part of Tarokina Pro and are subject to its license terms.

---
*Last updated: 2025-12-13*
