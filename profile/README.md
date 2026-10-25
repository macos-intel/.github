# macOS Homebrew Intel

<!-- Inline HTML because Markdown's image syntax cannot set a width. The
     images live in homebrew-tap/img, the single copy the site also uses. -->
<p align="center">
  <img src="https://raw.githubusercontent.com/macos-intel/homebrew-tap/main/img/homebrew-intel.svg"
    alt="macOS Homebrew Intel logo: a beer mug with the Intel logo in its foam"
    width="200">
</p>

Working to keep macOS Intel Brew builds maintained.

homebrew-core stopped publishing Intel (x86_64) bottles. Our tap keeps
building them for an explicit, growing list of formulae, so you pour a
prebuilt bottle instead of compiling.

```bash
brew tap macos-intel/tap
brew trust macos-intel/tap
brew install macos-intel/tap/cmake
```

Install formulae fully qualified (`macos-intel/tap/<name>`): a bare name
installs core's version.

- 🌐 Website: <https://macos-intel.github.io/homebrew-tap/>
- 🍺 Tap: [macos-intel/homebrew-tap](https://github.com/macos-intel/homebrew-tap)
- 📦 Bottles: [releases](https://github.com/macos-intel/homebrew-tap/releases)

## Support

Intel Macs on macOS Sequoia 15 with Homebrew in `/usr/local`. Tahoe 26
support is planned.

Homebrew plans to stop running on Intel in or after September 2027. This
project ends then, unless a separate decision extends it.

<p align="center">
  <img src="https://raw.githubusercontent.com/macos-intel/homebrew-tap/main/img/homebrew-intel-bot.svg"
    alt="The macOS Homebrew Intel bot, a cheerful robot raising a mug"
    width="140">
</p>

Bottles are built and published by our bot. Not affiliated with or endorsed
by Homebrew.
