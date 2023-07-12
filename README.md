# Ecoregions by "Flora Fungorum Ucrainicae"

![Ecoregions according to the "Flora Fungorum Ucrainicae"](path)

## Origin of the data

This regionalization was originally published by Heluta (1989), to illustrate the distribution of powdery mildew fungi across Ukraine, and further was used in the series "Flora Fungorum Ucrainicae", as well as individual publications and thesis in Mycology. The regionalization was based mainly on the current at that time Geobotanical zonation of the URSR (Barbarych et. al, 1977).

Since both names and accepted abbreviations of regions originally were in Russian, we adopted the translation made by Akulov et al. (2003), with some additions from a later publication by Prylutskyi & Chvikov (2020):

**UPD 2023:** Ukrainian names and abbreviations, as well as English names of the regions, updated according to [Heluta,2023](https://ukrbotj.co.ua/archive/80/3/199).

VFS — Volyn (Volhynian) Forest-Steppe, MCr — Mountain Crimea, DGMS — Donetsk Grass-Meadow Steppe, TR — Transcarpathia, WFS — Western Forest-Steppe, WP — Western Polissya, WUF — Western Ukrainian Forests, CF — Carpathian Forests, CrFS — Crimean Forest-Steppe, CrS — Crimean Steppe, LGMS — Left Bank Grass-Meadow Steppe, LGS — Left Bank Grass Steppe, LFS — Left Bank Forest-Steppe, LP — Left Bank Polissya, LesP — Lesser Polissya, SCCr — South Coast of Crimea, RGMS — Right Bank Grass-Meadow Steppe, RGS — Right
Bank Grass Steppe, CCF — Cis-Carpathian Forests, RFS — Right Bank Forest-Steppe, PS — Polynovyi (Artemisia) Steppe, RF — Roztochchya Forests, SGMS — Starobilsk Grass-Meadow Steppe, EEUF — East European (Central Russian) Upland Forests, KFS — Kharkiv Forest-Steppe, CP — Central (Right Bank) Polissya

## Dataset description

Dataset contains GIS vector layers with the polygons of ecoregions, in the following formats: Geopackage, KML, and Esri Shapefile. Polygons have been drawn manually using QGIS software, following verbal descriptions of the borders of regions from Heluta (1989). QGIS project file is also included.

CRS: EPSG:3857 - WGS 84 / Pseudo-Mercator

Charset Encoding: UTF-8

## Attributes descriptions

fid - Unique identifier for each polygon
Name - Accepted abbreviated name for the region in Ukrainian
NameEng - Abbreviated name for the region, translated into English
NameFullUA - Full Ukrainian name of a region
NameFul - Full English name of a region
NatZone - Natural zone according to the source (Heluta, 1989), in Ukrainian
Ecoregions - Name of the Terrestrial Ecoregion (TEOW) (Olson et al., 2001), which covers most of the area of a given region
Note: KML file has additional system fields, not contain attribute information.

## References

1. Heluta, V.P. (2023) A critical revision of the powdery mildew fungi (Erysiphaceae, Ascomycota) of Ukraine: Erysiphe sect. Microsphaera. Ukrainian Botanical Journal. 2023. 80 (3). https://doi.org/10.15407/ukrbotj80.03.199
2. Heluta, V.P. (1989) Powdery Mildews. Flora Fungorum Ucrainicae. Kyiv: Naukova dumka [In Russian: Гелюта, В.П. (1989) Флора грибов Украины: Мучнисторосяные грибы. Киев: Наукова думка]
3. Barbarych, A.I. (Ed.) (1977)Geobotanical zonation of the URSR. Kyiv: Naukova Dumka [in Ukrainian: Геоботанічне районування Української РСР. Київ: Наукова думка]
4. Akulov, O.Yu.; Usichenko, A.S.; Leontyev, D.V.; Yurchenko, E.O.; Prydiuk, M.P. (2003) Annotated checklist of aphyllophoroid fungi of Ukraine. Mycena 2:1–76.
5. Chvikov, V.; Prylutskyi, О. (2020) Annotated checklist of Hygrophoraceae (Agaricales, Basidiomycota) of Ukraine. Biodivers. Ecol. Exp. Biol. 22, 6–23. https://doi.org/10.34142/2708-5848.2020.22.2.01
6. Olson, D. M., Dinerstein, E., Wikramanayake, E. D., Burgess, N. D., Powell, G. V. N., Underwood, E. C., D'Amico, J. A., Itoua, I., Strand, H. E., Morrison, J. C., Loucks, C. J., Allnutt, T. F., Ricketts, T. H., Kura, Y., Lamoreux, J. F., Wettengel, W. W., Hedao, P., Kassem, K. R. 2001. Terrestrial ecoregions of the world: a new map of life on Earth. Bioscience 51(11):933-938.
