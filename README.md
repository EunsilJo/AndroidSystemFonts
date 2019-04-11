# AndroidSystemFonts

Path of Android SDK fonts.xml - ~/Library/Android/sdk/platforms/android-28/data/fonts/fonts.xml

#### Default system fonts are Roboto(en), NotoSansCJK(ko, ja) on Android 9.0(P, api 28)

### en

| FONT FAMILY                 | STYLE  | ANDROID VERSION             |                           |     |     |     |     |
|:----------------------------|:-------|:----------------------------|:--------------------------|:----|:----|:----|:----|
|                             |        | 4.4                         | 5.0                       | 6.0 | 7.0 | 8.0 | 9.0 |
|                             |        | TYPEFACE                    |                           |     |     |     |     |
| sans-serif **(default)**         | normal | Roboto-Regular.ttf          |                           |     |     |     |     |
|                             | bold   | Roboto-Bold.ttf             |                           |     |     |     |     |
|                             | italic | Roboto-Italic.ttf           |                           |     |     |     |     |
| sans-serif-thin             | normal | Roboto-Thin.ttf             |                           |     |     |     |     |
| sans-serif-light            | normal | Roboto-Light.ttf            |                           |     |     |     |     |
| sans-serif-medium           | normal | -                           | Roboto-Medium.ttf         |     |     |     |     |
| sans-serif-black            | normal | -                           | Roboto-Black.ttf          |     |     |     |     |
| sans-serif-condensed        | normal | RobotoCondensed-Regular.ttf |                           |     |     |     |     |
|                             | bold   | RobotoCondensed-Bold.ttf    |                           |     |     |     |     |
|                             | italic | RobotoCondensed-Italic.ttf  |                           |     |     |     |     |
| sans-serif-condensed-light  | normal | -                           | RobotoCondensed-Light.ttf |     |     |     |     |
| sans-serif-condensed-medium | normal | -                           | -                         | -   | -   |     | RobotoCondensed-Medium.ttf |
| serif                       | normal | DroidSerif-Regular.ttf      | NotoSerif-Regular.ttf     |     |     |     |     |
|                             | bold   | DroidSerif-Bold.ttf         | NotoSerif-Bold.ttf        |     |     |     |     |
|                             | italic | DroidSerif-Italic.ttf       | NotoSerif-Italic.ttf      |     |     |     |     |
| monospace                   | normal | -                           | DroidSansMono.ttf         |     |     |     |     |
| serif-monospace             | normal | -                           | CutiveMono.ttf            |     |     |     |     |
| casual                      | normal | -                           | ComingSoon.ttf            |     |     |     |     |
| cursive                     | normal | DroidSerif-Regular.ttf	     | DancingScript-Regular.ttf |     |     |     |     |
|                             | bold   | DroidSerif-Bold.ttf         | DancingScript-Bold.ttf    |     |     |     |     |
| sans-serif-smallcaps        | normal | -                           | CarroisGothicSC-Regular.ttf |     |     |     |     |

## ko/ja

| FONT FAMILY                 | STYLE  | ANDROID VERSION |                           |     |     |     |     |
|:----------------------------|:-------|:----------------|:--------------------------|:----|:----|:----|:----|
|                             |        | 4.4             | 5.0                       | 6.0 | 7.0 | 8.0 | 9.0 |
|                             |        | TYPEFACE        |                           |     |     |     |     |
| serif                       | normal | -               | -                         | -   | -   | -   | NotoSerifCJK-Regular.ttc |
| others **(default)**             | normal | -               | NotoSansKR-Regular.otf / NotoSansJP-Regular.otf |     | NotoSansCJK-Regular.ttc |     |     |

### weight

| TYPEFACE | WEIGHT |
|:---------|:-------|
| -Thin	   | 100    |
| -Light   | 300    |
| -Regular   | 400    |
| -Medium   | 500    |
| -Black   | 900    |
| -Bold   | 700    |


### Fonts in XML

https://developer.android.com/guide/topics/ui/look-and-feel/fonts-in-xml

positive  : not depends on device spec

negative  : Font size increases APK size


### Downloadable Fonts

https://developer.android.com/guide/topics/ui/look-and-feel/downloadable-fonts

<img src="https://developer.android.com/guide/topics/ui/images/look-and-feel/downloadable-fonts/downloadable-fonts-process.png" width="400"/>

positive  : Font size **NOT** increases APK size

negative  : depends on device spec - **Android 4.4 version, Google Play Service 11 version, api level 26 or higher**

