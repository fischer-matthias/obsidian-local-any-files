# Installation Guide for Local Any Files Plugin

## ✅ Plugin Successfully Compiled

This plugin has been compiled and is ready to use in Obsidian!

## Installation Methods

### Method 1: Manual Installation (Recommended)

1. **Download the required files:**
   - `main.js` (compiled plugin code)
   - `manifest.json` (plugin metadata)
   - `styles.css` (plugin styles)

2. **Install in Obsidian:**
   - Navigate to your Obsidian vault folder
   - Go to `.obsidian/plugins/` directory (create it if it doesn't exist)
   - Create a new folder named `local-any-files`
   - Copy `main.js`, `manifest.json`, and `styles.css` into this folder

3. **Enable the plugin:**
   - Open Obsidian
   - Go to Settings → Community Plugins
   - Disable "Safe Mode" if prompted
   - Find "Local Any Files" in the installed plugins list
   - Toggle it on

### Method 2: Clone Repository

```bash
cd /path/to/your/vault/.obsidian/plugins/
git clone https://github.com/fischer-matthias/obsidian-local-any-files.git local-any-files
cd local-any-files
git checkout copilot/compile-release-for-obsidian-plugin
```

Then enable the plugin in Obsidian settings.

## Verification

After installation, you should see "Local Any Files" plugin in your:
- Settings → Community Plugins → Installed plugins
- Command Palette (Ctrl/Cmd + P) with commands like:
  - "Local any files: Download attachments from links"
  - "Local any files: Download attachments from links (use previous options)"

## Plugin Information

- **Name:** Local Any Files
- **Version:** 1.3.5
- **ID:** local-any-files
- **Author:** ShermanTsang
- **Minimum Obsidian Version:** 0.15.0

## Build Details

The plugin was compiled using:
- TypeScript 4.7.4
- ESBuild 0.17.3
- Production mode (minified and optimized)

**Compiled file sizes:**
- main.js: 28 KB
- manifest.json: 266 bytes
- styles.css: 7.3 KB

## Features

This plugin helps you download external files from your notes and store them locally in your vault. It supports:

- Wide range of file types (images, documents, archives, media files, etc.)
- Flexible processing options (current file, folder, or entire vault)
- Customizable storage paths and file naming
- Real-time progress tracking

For more information, see the [README.md](README.md) file.

## Troubleshooting

If the plugin doesn't appear:
1. Make sure all three files are in the correct folder
2. Restart Obsidian
3. Check that "Safe Mode" is disabled in Settings
4. Look for error messages in the Developer Console (Ctrl+Shift+I)

## Support

For issues or questions:
- [GitHub Issues](https://github.com/fischer-matthias/obsidian-local-any-files/issues)
