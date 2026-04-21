# homebrew-pinelabs

Homebrew tap for [Pine Labs MCP Server](https://github.com/plural-pinelabs/pinelabs-online-mcp).

## Install

```bash
brew install plural-pinelabs/pinelabs/pinelabs-mcp-server
```

That single command taps the repo and installs the formula automatically.

## Usage

```bash
# Show help
pinelabs-mcp-server --help

# Run with stdio transport
pinelabs-mcp-server stdio \
  --client-id YOUR_CLIENT_ID \
  --client-secret YOUR_CLIENT_SECRET \
  --env uat
```

## Upgrade

```bash
brew update
brew upgrade pinelabs-mcp-server
```

## Uninstall

```bash
brew uninstall pinelabs-mcp-server
brew untap plural-pinelabs/pinelabs
```
