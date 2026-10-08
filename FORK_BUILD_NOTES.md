# Fork build notes

This fork is built from upstream `storytold/pdfcraft` at v0.3.0 with no source changes.

The build includes the complete Traditional Chinese (`zh-hant`) UI catalog
(`crates/ui-egui/src/i18n/zh-hant.tsv`, 1855 strings, same coverage as the
Japanese catalog). On systems with a `zh-TW`/`zh-HK`/`zh-MO` locale the app
starts in Traditional Chinese automatically; it can also be switched manually
under Preferences → Interface language → 繁體中文.
