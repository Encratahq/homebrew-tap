# Encrata Homebrew Tap

Official [Homebrew](https://brew.sh) tap for the **Encrata CLI** — email, phone, IP, domain, company, and OSINT intelligence lookups from your terminal.

## Install

```bash
brew tap encratahq/tap
brew install encrata
```

Then authenticate

```bash
encrata config set-key YOUR_API_KEY
```

Get your API key at [encrata.com/settings/api-keys](https://encrata.com/settings/api-keys).

## Upgrade

```bash
brew update
brew upgrade encrata
```

## Uninstall

```bash
brew uninstall encrata
brew untap encratahq/tap
```

## Supported platforms

| OS | Architectures |
|----|---------------|
| macOS | Apple Silicon (arm64), Intel (amd64) |
| Linux | arm64, amd64 |

Windows users: install via `npm install -g encrata-cli` or download a binary from [Releases](https://github.com/Encratahq/cli/releases).

## Links

- CLI source: https://github.com/Encratahq/cli
- Website: https://encrata.com
