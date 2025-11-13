# Bluetooth Manager - Device pairing and audio connectivity

**Package**: `@system/bt`
**Version**: 0.1.0
**Repository**: `pkg-system-bt`

## Overview

Bluetooth Manager - Device pairing and audio connectivity

## Installation

### Prerequisites

This package requires the following external commands:

- `bluetoothctl`
- `dmenu`
- `git`
- `rofi`
- `scanner`

### Using pkg-cli

```bash
# Install from GitHub
pkg-cli install @system/bt

# Or install from local source
cd ~/.pkgs
stow bt
```

## Usage

### System Integration

This package provides system integration for bluetooth manager - device pairing and audio connectivity.

```bash
# Connect to a Bluetooth device
bt connect

# Disconnect
bt disconnect

# Show status
bt status
```

## Configuration

Configuration files are typically stored in:
- `~/.config/bt/` - User configuration
- `~/.local/share/bt/` - Application data

## Uninstallation

```bash
# Using pkg-cli
pkg-cli uninstall @system/bt

# Or manual unstow
cd ~/.pkgs
stow -D bt
```

## Development

See [CLAUDE.md](CLAUDE.md) for development guidelines and AI assistance instructions.

## License

MIT License - See [LICENSE](LICENSE) file for details.

## Support

- **Issues**: [GitHub Issues](https://github.com/andronics/pkg-system-bt/issues)
- **Discussions**: [GitHub Discussions](https://github.com/andronics/pkg-system-bt/discussions)
- **Documentation**: [pkgs ecosystem docs](https://github.com/andronics/.pkgs)

## Version History

See [CHANGELOG.md](CHANGELOG.md) for version history.
