# vfox-chromedriver

A [vfox](https://github.com/version-fox/vfox) plugin for [ChromeDriver](https://chromedriver.chromium.org/) - WebDriver for Chrome.

## Installation

```bash
# With mise
mise install vfox:mise-plugins/vfox-chromedriver@131.0.6778.69

# With vfox
vfox add mise-plugins/vfox-chromedriver
vfox install chromedriver@131.0.6778.69
```

## Usage

```bash
# With mise
mise use vfox:mise-plugins/vfox-chromedriver@131.0.6778.69
chromedriver --version

# Or run directly
mise x vfox:mise-plugins/vfox-chromedriver@131.0.6778.69 -- chromedriver --version
```

## How it works

This plugin fetches ChromeDriver versions from Google's [Chrome for Testing](https://googlechromelabs.github.io/chrome-for-testing/) API and downloads the appropriate binary for your platform.

Supported platforms:
- Linux (x86_64)
- macOS (x86_64, arm64)
- Windows (x86, x64)

## License

Apache-2.0
