# Apple fonts documentation (WIP)
This repo documents Apple fonts found in Apple's official websites and its platforms. This is a work-in-progress (WIP).

## SF Pro
> This neutral, flexible, sans-serif typeface is the system font for iOS, iPad OS, macOS and tvOS. SF Pro features nine weights, variable optical sizes for optimal legibility, and includes a rounded variant. SF Pro supports over 150 languages across Latin, Greek, and Cyrillic scripts.

The main corporation font for Apple, used mostly in its website and the UI on iOS and macOS. There are 3 styles:
 - **SF Pro Text**: 9 weights, along with italic variant.
 - **SF Pro Display**: 9 weights, along with italic variant.
 - **SF Pro Rounded**: 9 weights. No italic variant. Not available in [variable format](https://web.dev/variable-fonts/). It uses **Display**'s optical size.

SF Pro Text and Display are also available in variable format, including italic. It allows iOS and macOS to dynamically control the optical size.

**Static version (for Text and Display optical sizes)**:
<table><thead><tr><th>Weight name</th><th>Value</th></tr></thead><tbody><tr><td>Ultralight</td><td>100</td></tr><tr><td>Thin</td><td>200</td></tr><tr><td>Light</td><td>300</td></tr><tr><td>Regular</td><td>400</td></tr><tr><td>Medium</td><td>500</td></tr><tr><td>Semibold</td><td>600</td></tr><tr><td>Bold</td><td>700</td></tr><tr><td>Heavy</td><td>800</td></tr><tr><td>Black</td><td>900</td></tr></tbody></table>

**Variable version** (predefined values):
<table><thead><tr><th>Weight name</th><th>Value</th></tr></thead><tbody><tr><td>Ultralight</td><td>30.925</td></tr><tr><td>Thin</td><td>110.725</td></tr><tr><td>Light</td><td>274.315</td></tr><tr><td>Regular</td><td>400</td></tr><tr><td>Medium</td><td>510</td></tr><tr><td>Semibold</td><td>590</td></tr><tr><td>Bold</td><td>700</td></tr><tr><td>Heavy</td><td>860</td></tr><tr><td>Black</td><td>1000</td></tr></tbody></table>
The minimum weight value is 1 and the maximum is 1000 (default: 400). For optical size, the min value is 17 and max is 28 (default: 28).

Those fonts can be downloaded from https://developer.apple.com/fonts. Last updated was on November 12, 2021, version ``17.1d1e1``. As Apple integrates SF Icons font into SF Pro, the font's size is larger as a result.

**Glyph count:**
- SF Pro Text / Display: 18,927 (18,146 for italic variant)
- SF Pro Rounded: 18,806

## SF Compact
> Sharing many features with SF Pro, SF Compact features an efficient, compact design that is optimized for small sizes and narrow columns. SF Compact is the system font for watchOS and includes a rounded variant.

The first font of the San Fransisco family, introduced in watchOS. There are 3 styles:
 - **SF Compact Text**: 9 weights, along with italic variant.
 - **SF Compact Display**: 9 weights, no italic variant.
 - **SF Compact Rounded**: 9 weights. No italic variant. Not available in [variable format](https://web.dev/variable-fonts/). It uses **Display**'s optical size.

SF Compact Text and Display are also available in variable format, including italic.

**Static version (for Text and Display optical sizes)**: same as SF Pro.

**Variable version** (predefined values):
<table><thead><tr><th>Weight name</th><th>Value</th></tr></thead><tbody><tr><td>Ultralight</td><td>59.254</td></tr><tr><td>Thin</td><td>200.5</td></tr><tr><td>Light</td><td>350.524</td></tr><tr><td>Regular</td><td>457.9</td></tr><tr><td>Medium</td><td>556</td></tr><tr><td>Semibold</td><td>656.2</td></tr><tr><td>Bold</td><td>790</td></tr><tr><td>Heavy</td><td>943</td></tr><tr><td>Black</td><td>1000</td></tr></tbody></table>

The minimum weight value is 1 and the maximum is 1000 (default: 1000). For optical size, the min value is 19 and max is 20 (default: 19).

Those fonts can be downloaded from https://developer.apple.com/fonts. Last updated was on November 12, 2021, version ``17.1d1e1``. As Apple integrates SF Icons font into SF Compact, the font's size is larger as a result.

**Glyph count:**
- SF Compact Text / Display / Rounded: 18,498 (17,879 for italic variant)

## SF Mono
> This monospaced variant of San Francisco enables alignment between rows and columns of text, and is used in coding environments like Xcode. SF Mono features six weights and supports Latin, Greek, and Cyrillic scripts.

It was introduced at WWDC 2016. There are 6 weights with italic variant. It used to have a variable format (as of August 11, 2020); however, it was removed on August 28, 2020.

**Variable version** (predefined values):
<table><thead><tr><th>Weight name</th><th>Weight value</th><th>Assigned YAXS value</th></tr></thead><tbody><tr><td>Light</td><td>294.6731</td><td>294.6731</td></tr><tr><td>Regular</td><td>400</td><td>324.3341</td></tr><tr><td>Medium</td><td>483.5351</td><td>320.7022</td></tr><tr><td>Semibold</td><td>571.3075</td><td>324.9394</td></tr><tr><td>Bold</td><td>683.293</td><td>335.8353</td></tr><tr><td>Heavy</td><td>900</td><td>294.6731</td></tr></tbody></table>

The minimum weight value is 294.6731 and the maximum is 900 (default: 294.6731). For [YAXS](https://web.dev/more-variable-font-options-in-chromium-83/#yaxs), the min value is 294.6731 and max is 900 (default: 294.6731).

The font can be downloaded from https://developer.apple.com/fonts. Last updated was on August 28, 2020, version ``16.0d2e1``.

**Glyph count:** 1,628 (1,324 for italic variant)
