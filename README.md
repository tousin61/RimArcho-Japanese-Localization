# RimArcho — Japanese Localization (日本語化)

Japanese language support for [RimArcho](https://github.com/ToumanLin/RimArcho).

This is an unofficial community translation project created to help bring Japanese language support to RimArcho.

The goal is to make RimArcho easier to use for Japanese-speaking RimWorld players and to contribute the translation to the official project.

## Localization Details

**Based on:** RimArcho v1.0.9  
**Language:** Japanese (ja)  
**Translation:** tousin61, with assistance from ChatGPT (OpenAI)

The localization includes:

- 3,762 standard translation entries and 81 auxiliary entries.
- Japanese language selection in the application settings.
- Automatic Japanese language detection.
- Translations for the main GUI and settings.
- Mod management, load order, and mod library interfaces.
- Error diagnostics and log analysis.
- Save management and compatibility checks.
- Mod packs, subscriptions, and update management.
- Texture optimization and background tasks.
- Japanese translations for Archo Monitor.

Mod names, original error logs, source code identifiers, and Steam Workshop descriptions are intentionally preserved in their original languages.

## Download

Download the localization package from this repository:

**RimArcho_Japanese_Localization_Submission.zip**

The package contains the Japanese translation data, source code changes, an integration patch, and documentation.

## Integration

This package is intended for the RimArcho developer or other contributors who wish to integrate Japanese localization into the application.

1. Download and extract the ZIP archive.
2. Review the included `README.md` and `VALIDATION.md`.
3. Apply `japanese-localization.patch` to the corresponding RimArcho source code.
4. Build the application and verify Japanese language selection.

The archive contains localization source changes, not a prebuilt Windows application.

## Testing

Japanese preview builds were tested on Windows, including language switching and major GUI screens.

Additional validation included:

- Translation key consistency checks.
- Format placeholder validation.
- Japanese localization tests.
- Patch application checks.
- Archo Monitor translation XML validation.

A complete regression test of the final submission has not yet been performed. Some rarely used or dynamically generated messages may remain in English.

## Contribution to the Official Project

I would be happy if the RimArcho developer considered integrating this localization into an official release.

The translation files and source code changes are provided to make integration and maintenance easier.

Corrections and improvements are welcome!

## Credits

**Original application:** [RimArcho by ToumanLin](https://github.com/ToumanLin/RimArcho)

**Japanese localization:** tousin61  
**Translation and development assistance:** ChatGPT (OpenAI)

Special thanks to the RimArcho developer for creating this useful tool for the RimWorld community!
