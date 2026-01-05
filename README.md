# Homebrew Legacy

A Homebrew tap providing legacy versions of formulae that are no longer available in the official Homebrew repository.

## 📦 Available Formulae

- **cmake@3.20.0** - CMake 3.20.0
- **cmake@3.28.4** - CMake 3.28.4
- **zbar@0.10** - ZBar barcode reader 0.10 (macOS only)

## 🚀 Installation

### Install a specific formula:
```bash
brew install hokix/legacy/<formula>
```

Example:
```bash
brew install hokix/legacy/cmake@3.20.0
```

### Or tap first, then install:
```bash
brew tap hokix/legacy
brew install cmake@3.20.0
```

### Using with Brewfile:
```ruby
tap "hokix/legacy"
brew "cmake@3.20.0"
brew "zbar@0.10"
```

## 📝 Purpose

This tap maintains legacy versions of packages that:
- Have been removed from the official Homebrew repository
- Are needed for compatibility with older projects
- Require specific versions no longer officially supported

## ⚠️ Note

These are legacy versions and may not receive updates. Use official Homebrew formulae when possible.

## 📚 Documentation

For general Homebrew help: `brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
