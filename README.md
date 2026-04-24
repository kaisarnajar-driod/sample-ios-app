# Sample iOS App

A sample iOS project used for testing [Transync](https://github.com/kaisarnajar-driod/translation-automation-tool) — the translation automation tool.

## Clone

```bash
git clone git@github.com:kaisarnajar-driod/sample-ios-app.git
```

## String Resources

- **Format:** iOS Localizable.strings
- **Path:** `SampleApp/en.lproj/Localizable.strings`
- **Translated output:** `SampleApp/{lang}.lproj/Localizable.strings`

## Add to Transync

```bash
transync add sample-ios-app git@github.com:kaisarnajar-driod/sample-ios-app.git \
  --strings-path SampleApp/en.lproj/Localizable.strings \
  --languages hi,ar,fr,es
```
