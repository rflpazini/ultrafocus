# ultrafocus

A dead simple CLI tool to block distracting websites and boost productivity. Customize your blacklist, focus on tasks, and reclaim your time.

<p align="center" width="100%">
    <img src="https://github.com/plutov/ultrafocus/blob/main/screenshots/domains.png" hspace="10" height="200px">
    <img src="https://github.com/plutov/ultrafocus/blob/main/screenshots/status.png" hspace="10" height="200px">
</p>

## Installation

Download the latest binary from the [releases page](https://github.com/plutov/ultrafocus/releases/latest) or use `go install`:

```bash
go install github.com/plutov/ultrafocus
```

## Usage

ultrafocus needs `sudo` to modify `/etc/hosts` file. It won't affect your existing configuration, the changes made by ultrafocus are separated by `#ultrafocus:start/end` comments.

```bash
sudo ultrafocus
```

## Supported platforms

- macOS
- Linux
- Windows

## Default blacklist

- facebook.com
- instagram.com
- tiktok.com
- twitter.com
- youtube.com
- netflix.com
- reddit.com

## Run tests

```bash
go test -v -race ./...
```
