# SheetDiff

A tool for comparing Excel files - Compare and visualize differences between two Excel files at the cell level.

## Download

| Platform | Download |
|----------|----------|
| Windows | [SheetDiff_x.x.x_x64_en-US.msi](https://github.com/mintsoft-app-series/sheetdiff-release/releases/latest) |
| macOS (Intel) | [SheetDiff_x.x.x_x64.dmg](https://github.com/mintsoft-app-series/sheetdiff-release/releases/latest) |
| macOS (Apple Silicon) | [SheetDiff_x.x.x_aarch64.dmg](https://github.com/mintsoft-app-series/sheetdiff-release/releases/latest) |
| Linux | [SheetDiff_x.x.x_amd64.AppImage](https://github.com/mintsoft-app-series/sheetdiff-release/releases/latest) |

## Key Features

### File Comparison
- **Supported formats**: `.xlsx`, `.xls`, `.csv`
- **Drag and drop**: Just drag and drop files to start comparing
- **Multi-sheet support**: Compare Excel files with multiple sheets

### Comparison Methods
- **Value comparison**: Check cell value changes
- **Formula comparison**: Detect formula changes separately
- **Key column matching**: Match rows by specific column value instead of row number

### Change Types
| Type | Description |
|------|-------------|
| Added | Exists only in compare file |
| Removed | Exists only in original file |
| Modified | Different values in both files |
| Unchanged | Same values |

### Filter Options
- **Range specification**: Compare only specific column/row ranges
- **Ignore case**: `A` = `a`
- **Ignore whitespace**: `"a b"` = `"ab"`
- **Ignore number formatting**: `1000` = `1,000`

### Export Results
- Export to Excel (.xlsx) format
- Export to CSV (UTF-8) format

### UI/UX
- Dark mode / Light mode
- 50+ languages supported
- Keyboard shortcuts

## System Requirements

| Platform | Requirements |
|----------|--------------|
| Windows | Windows 10 or later (64-bit) |
| macOS | macOS 10.15 (Catalina) or later |
| Linux | Ubuntu 20.04 or equivalent distribution |

## Installation

### Windows
1. Download the `.msi` file
2. Run the installer
3. Follow the installation wizard

### macOS
1. Download the `.dmg` file
2. Open the DMG file
3. Drag SheetDiff app to the Applications folder
4. Run the following command in Terminal to remove quarantine attribute:
   ```bash
   sudo xattr -rd com.apple.quarantine /Applications/SheetDiff.app
   ```

### Linux
1. Download the `.AppImage` file
2. Grant execute permission: `chmod +x SheetDiff_*.AppImage`
3. Run: `./SheetDiff_*.AppImage`

## How to Use

1. **Select files**: Choose or drag and drop the original file and comparison file
2. **Configure options**: Adjust comparison options if needed (ignore case, specify range, etc.)
3. **Run comparison**: Click the "Compare" button
4. **Review results**: Check the list of changes and navigate to cell locations
5. **Export**: Save results to Excel or CSV if needed

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `↑` / `k` | Previous change |
| `↓` / `j` | Next change |
| `Ctrl+O` | Select original file |
| `Ctrl+P` | Select compare file |
| `Ctrl+E` | Export to Excel |
| `Ctrl+S` | Export to CSV |
| `ESC` | Close results |

## License

MIT License

## Feedback

Please report bugs or feature requests on [GitHub Issues](https://github.com/mintsoft-app-series/sheetdiff-release/issues).
