# Automatic Advanced Settings Expander

Automatically expands the advanced settings in the Settings app by hooking `setInitialExpandedChildrenCount` in PreferenceGroup.
I hate to always expand them myself every-time.

Should work on all Android versions where the Settings app uses one of

- androidx.preference.PreferenceGroup
- android.preference.PreferenceGroup
- android.support.v7.preference.PreferenceGroup

Please report where it stops working so that I can edit the minSdkVersion or add missing classes.

| before | after |
|--------|-------|
|![before](https://github.com/binarynoise/XposedModulets/raw/main/metadata/de.binarynoise.AutomaticAdvancedSettingsExpander/en-US/images/phoneScreenshots/1-before.png)|![after](https://github.com/binarynoise/XposedModulets/blob/main/metadata/de.binarynoise.AutomaticAdvancedSettingsExpander/en-US/images/phoneScreenshots/2-after.png)|

# Source
<https://github.com/binarynoise/XposedModulets/tree/main/AutomaticAdvancedSettingsExpander>

# License
This module is licensed under the [European Union Public Licence (EUPL) v. 1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12)
