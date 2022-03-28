![Nord Theme for Nova logo](https://github.com/GwynethLlewelyn/Nord.novaextension/blob/master/extension.png?raw=true)

# Nord Theme for Nova

Based on the fantastic work made by the [Arctic Ice Studio Team for Coda 2](https://github.com/arcticicestudio/nord-coda/), which is released under a MIT license.

## Instructions

Of course, you need to have [Nova](https://panic.com/nova) installed (FYI, it only works under macOS).

If you're a proud owner of Nova, you ought to be able to go to **Extensions > Extension Library > Themes (tab)** and pick the theme from there — search for `Nord`.

If that doesn't work, just clone this project (or download it from the releases page), it'll magically turn into a 'component' thingy, and you can then double-click it to add this theme to Nova!

## Swatch

If you wish to add the Nord theme palette for the Nova 5+ built-in Color Picker, you can install it from inside the package for this extension, under [`Swatches\Nord.json`](Swatches\Nord.json). Until I figure out how this works automatically, you will need to upload it manually: from the Color Picker, click on the gear icon, and select `Swatches/Import...`

**Note:** the Color Picker also seems to be able to directly open Adobe Swatch Exchange (ASE) files, so you probably can use [the official `nord.ase` file](https://www.nordtheme.com/docs/swatches) instead).

## Disclaimer

[Nova](https://panic.com/nova) is a code editor developed by [Panic Inc.](https://panic.com/)

I'm neither an employee, nor a collaborator, nor a stakeholder in either Panic Inc. and/or Arctic Ice Studio. I just love both their work as a faithful fan!

Please take into account that I hardly know what I'm doing. Hope it works for you. This is being released for the sole purpose of testing how designing themes for Nova work; no infringements are intended; also, I might be tweaking this theme frequently, as I start figuring out how the colour assignments actually work; thus, _caveat utilitor_.

## Special thanks

Thanks to [Dennis Osaj](https://github.com/dennisosaj), designer of the wonderful [advanced PHP extension](https://extensions.panic.com/extensions/dennisosaj/dennisosaj.advancedPHP/) as well as the [Varia theme](https://extensions.panic.com/extensions/dennisosaj/dennisosaj.VariaTheme/), who pointed out that I should add a few more styling classes to deal with the specificities of `advanced PHP` — as well as XML, HTML and JavaScript, which are better supported by the Varia Theme.

This version of the `Nord Theme for Nova` is adding experimental support for `advanced PHP`, but be advised that things may still be broken or not display properly... I'm still learning about all these things!

## Licenses and acknowledgements

For this package: [MIT License](LICENSE.md)

For the Nord theme colours: Sven Greb/Arctic Ice Studio [MIT License](https://github.com/arcticicestudio/nord/blob/develop/LICENSE.md)

Nova is a trademark of Panic Inc.

## My GPG Fingerprint

In case you need it to send me encrypted email:

> CE8A 6006 B611 850F 1275 72BA D93E AA3D C4B3 E1CB

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=GwynethLlewelyn_Nord.novaextension&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=GwynethLlewelyn_Nord.novaextension)
