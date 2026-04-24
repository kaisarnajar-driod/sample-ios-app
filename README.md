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

### Example (`Localizable.strings`)

```
"label_studio_disclaimer_subtitle" = "Free consultation and custom fitting are required with an optician at selected Lenskart showrooms.";
"sub_title_empty_view" = "Lenskart is working hard to expand pickup points across the country. We are coming soon to your locality.";
"label_unserviceable_to_fourth_floor" = "We'll be unable to provide service to floors located on the 4th floor and higher if there is no elevator available.";
"label_pupillary_distance_click_suggestion" = "Keep your face aligned & capture a picture to find your Pupillary Distance (PD)";
"msg_successfully_password_sent" = "Check your email - A link to reset password has been sent to your email";
```

## Add to Transync

```bash
transync add sample-ios-app git@github.com:kaisarnajar-driod/sample-ios-app.git \
  --strings-path SampleApp/en.lproj/Localizable.strings \
  --languages hi,ar,fr,es
```
