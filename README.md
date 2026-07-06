# Obsidian Plugin Collection

A snapshot of the Obsidian plugins I use, bundled as ready-to-install zip files in the [Releases](https://github.com/Real-Fruit-Snacks/obsidian-plugins/releases) section.

A browsable index of every plugin, with links to its Obsidian community listing and its source repository, is available on the [plugin index page](https://real-fruit-snacks.github.io/obsidian-plugins/).

## What is included

Each zip in a release contains a single plugin folder with only the files Obsidian needs to run it:

- `main.js`
- `manifest.json`
- `styles.css` (when the plugin ships one)

Personal configuration (`data.json`), backups, and development artifacts are deliberately excluded. The `all-plugins.zip` asset bundles every plugin folder in one archive.

## Installation

1. Download a plugin zip (or `all-plugins.zip`) from the latest release.
2. Extract it into your vault's `.obsidian/plugins/` directory so each plugin sits in its own folder.
3. Reload Obsidian, then enable the plugin under Settings > Community plugins.

## Plugins

### Community plugins

| Plugin | Version | Description | Links |
| --- | --- | --- | --- |
| Advanced Tables | 0.23.2 | Improved table navigation, formatting, manipulation, and formulas. | [Community](https://community.obsidian.md/search?type=plugin&q=Advanced%20Tables) / [GitHub](https://github.com/tgrosinger/advanced-tables-obsidian) |
| Attachment Management | 0.12.1 | Customize your attachment path of notes independently with variables and auto rename it on change. | [Community](https://community.obsidian.md/search?type=plugin&q=Attachment%20Management) / [GitHub](https://github.com/trganda/obsidian-attachment-management) |
| belki | 0.4.0 | A minimal Todoist-like task manager using local Markdown files. | [Community](https://community.obsidian.md/search?type=plugin&q=belki) / [GitHub](https://github.com/aribuga/obsidian-belki-tasks) |
| Commander | 0.5.5 | Customize your workspace by adding commands everywhere, create Macros and supercharge your mobile toolbar. | [Community](https://community.obsidian.md/search?type=plugin&q=Commander) / [GitHub](https://github.com/jsmorabito/obsidian-commander) |
| Cove | 1.0.2 | Bookmark manager with four switchable layouts. Each bookmark is a Markdown file with YAML frontmatter. | [Community](https://community.obsidian.md/search?type=plugin&q=Cove) / [GitHub](https://github.com/Real-Fruit-Snacks/Cove) |
| Dataview | 0.5.68 | Complex data views for the data-obsessed. | [Community](https://community.obsidian.md/search?type=plugin&q=Dataview) / [GitHub](https://github.com/blacksmithgu/obsidian-dataview) |
| File Hider | 1.1.1 | Allows hiding files and folders in the built-in file explorer. | [Community](https://community.obsidian.md/search?type=plugin&q=File%20Hider) / [GitHub](https://github.com/eldritch-oliver/file-hider) |
| Git | 2.38.5 | Integrate Git version control with automatic backup and other advanced features. | [Community](https://community.obsidian.md/search?type=plugin&q=Git) / [GitHub](https://github.com/Vinzent03/obsidian-git) |
| Iconic | 1.1.9 | Customize your icons and their colors directly from the UI, including tabs, files and folders, bookmarks, tags, properties, and ribbon commands. | [Community](https://community.obsidian.md/search?type=plugin&q=Iconic) / [GitHub](https://github.com/gfxholo/iconic) |
| Paste URL into selection | 1.11.4 | Paste URL "into" selected text to create markdown links. | [Community](https://community.obsidian.md/search?type=plugin&q=Paste%20URL%20into%20selection) / [GitHub](https://github.com/denolehov/obsidian-url-into-selection) |
| Settings Search | 1.3.10 | Globally search settings in Obsidian. | [Community](https://community.obsidian.md/search?type=plugin&q=Settings%20Search) / [GitHub](https://github.com/javalent/settings-search) |
| Style Settings | 1.0.9 | Offers controls for adjusting theme, plugin, and snippet CSS variables. | [Community](https://community.obsidian.md/search?type=plugin&q=Style%20Settings) / [GitHub](https://github.com/obsidian-community/obsidian-style-settings) |
| Tag Wrangler | 0.6.4 | Rename, merge, toggle, and search tags from the tags view. | [Community](https://community.obsidian.md/search?type=plugin&q=Tag%20Wrangler) / [GitHub](https://github.com/pjeby/tag-wrangler) |
| Vim Motions | 0.35.0 | Enhances the built-in Vim mode with Markdown-aware text objects, structural navigation, workspace keyboard control, and a polished Neovim-native experience. | [Community](https://community.obsidian.md/search?type=plugin&q=Vim%20Motions) / [GitHub](https://github.com/saberzero1/motions) |

### Unofficial plugins

These are not in the official community plugin directory and are installed directly from GitHub.

| Plugin | Version | Description | Links |
| --- | --- | --- | --- |
| Amazon Order Sync | 1.1.0 | Receives order data from the Amazon Order Sync browser extension and creates markdown notes. | [GitHub](https://github.com/Real-Fruit-Snacks/amazon-order-sync) |
| GitHub Plugin Updater | 1.2.2 | Download and install unofficial plugins directly from GitHub. | [GitHub](https://github.com/Real-Fruit-Snacks/obsidian-github-updater) |
| Gym Tracker | 1.0.2 | Track gym workouts, exercise volume, streaks, and history on mobile and desktop. | [GitHub](https://github.com/Real-Fruit-Snacks/obsidian-gym-tracker) |
| Nested Vaults | 1.1.0 | Scope your vault to a specific folder, effectively treating it as a nested sub-vault. | [GitHub](https://github.com/Real-Fruit-Snacks/obsidian-nested-vaults) |
| Tidemark | 1.0.2 | Replace {{variables}} with YAML frontmatter values on demand. | [GitHub](https://github.com/Real-Fruit-Snacks/Tidemark) |
| Wake | 1.0.1 | A keyboard-first task manager with projects, recurring tasks, priorities, smart views, and a permanent logbook in a self-contained panel. | [GitHub](https://github.com/Real-Fruit-Snacks/Wake) |
| Wayback Linker | 1.0.3 | Archive external links in the active note with the Wayback Machine and replace them with snapshot URLs. | [GitHub](https://github.com/Real-Fruit-Snacks/wayback-linker) |

## Notes

- All plugins remain the property of their respective authors and are distributed here only as a personal backup and convenience bundle. See each plugin's repository for its license.
- Versions reflect the snapshot date of the release and may lag behind upstream.
