# homebrew-tap

This tap used to ship Hidebar, a macOS menu bar utility that hid menu bar icons
behind a separator.

**Hidebar is discontinued.** macOS 27 collapses menu bar icons that do not fit
behind an overflow arrow, including the ones that used to vanish behind the
notch, so the app is no longer needed. The cask has been removed and no new
versions will be published.

## Uninstall

If you installed Hidebar from this tap:

```bash
brew uninstall --cask --zap hidebar
brew untap pod2metra/tap
```

`--zap` also removes the app's preferences.
