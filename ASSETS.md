# Local visual assets

## Roots and soil

`public/assets/roots-soil.png` is a decorative transparent vignette generated with the built-in image-generation tool. It is not geographic, crop, weather or satellite evidence. Used sparingly at the right edge of page headers.

Generation prompt:

> Use case: scientific-educational. Asset type: subtle natural-history header vignette for an agricultural finance application, with a transparent background. A precise archival scientific ink study of a crop root system viewed as a soil cross-section, no plant canopy, fine irregular branching dark brown and forest ink roots extending down into a small cut edge of lightly textured warm earthy soil on the right. Restrained natural history field-journal engraving, realistic delicate linework, no decorative frame, no labels, no numbers, no text or lettering, no logos, no sky or landscape. Horizontal airy composition: root and soil vignette only on right third; two thirds left is truly transparent empty space. The root study fades softly into transparency along its edges. Quiet, precise, sophisticated, low contrast, warm paper compatible. Not wallpaper, not a chart, not a photo landscape.

The older generated `farmland.png` is retained as an unused reference asset. It is no longer used by the application.

## Brand and typography

`public/assets/suyana-logo.svg` is a local SUYANA wordmark with a leaf motif, created for the demonstration. It is not a supplied official brand asset. Replace this single file when an official vector is available.

Newsreader headings and Inter operational text are bundled from Fontsource. Bootstrap Icons supplies the consistent icon family. No remote font/image/icon request occurs at runtime.

## Offline geography

`public/maps/argentina-provinces.geojson` contains simplified Argentine ADM1 geographic reference geometry from geoBoundaries gbOpen, boundary ID **ARG-ADM1-19177384**, representing **2006**, source **Wikimedia**. The dataset metadata specifies **CC BY 2.5 Generic**. No geometry edits were made after downloading the simplified release.

- [geoBoundaries dataset metadata](https://www.geoboundaries.org/api/current/gbOpen/ARG/ADM1/)
- [Pinned simplified GeoJSON release](https://media.githubusercontent.com/media/wmgeolab/geoBoundaries/9469f09/releaseData/gbOpen/ARG/ADM1/geoBoundaries-ARG-ADM1_simplified.geojson)
- [License](https://creativecommons.org/licenses/by/2.5/)

Attribution is displayed on the map. Geographic reference outlines are not loan or model data, are not a statement about disputed boundaries, and do not verify field ownership. The older hand-drawn map files remain unused references. Generated field polygons/points are in the shared synthetic dataset and `public/data/fields.geojson`.
