# UPLB GS Citation Style

This repository contains a custom Citation Style Language file, `./UPLB-GS-style.csl`, designed in accordance to the University of the Philippines Los Banos (UPLB) Graduate School manuscript requirements.

## Style Rules Implemented

-   ALL CAPS for author names in the bibliography
-   Surname first for the lead author; initials first for succeeding authors
-   No italics for journal names and book titles
-   Italicized scientific terms where applicable (for example, `et al.` and Latin species names when marked in Zotero)
-   Bibliography spacing format: single spacing within entries, double spacing between entries

## Install in Zotero

1.  Download or locate [`UPLB-GS-style.csl`](./UPLB-GS-style.csl) on your computer.
2.  Open Zotero desktop.
3.  Go to `Edit > Preferences` (Windows) or `Zotero > Settings` (Mac).
4.  Open the `Cite` tab, then the `Styles` sub-tab.
5.  Click the `+` (plus) button below the styles list.
6.  Select `UPLB-GS-style.csl`, then click `Open`.
7.  The style will appear as `UPLB GS Style`.

## Quick Test

1.  Open a blank document in Microsoft Word or Google Docs.
2.  Open the Zotero tab/menu, then click `Document Preferences`.
3.  Select `UPLB GS Style`, then click `OK`.
4.  Click `Add/Edit Citation` and insert several item types (for example: journal article, book, thesis).
5.  Press `Enter` a few times to add space, then click `Add/Edit Bibliography`.
6.  Zotero will generate the references using UPLB GS formatting rules.

## Real Output Examples (from `examples.docx`)

### In-Text Citation Examples

1.  Book: `(Mayo et al., 1997)`
2.  Book section: `(Chao and Chiu, 2016)`
3.  Journal article: `(Abdullah et al., 2020)`
4.  Software: `(R Core Team, 2020)`
5.  Thesis: `(Grayum, 1984)`
6.  Webpage: `(Global Biodiversity Information Facility, 2024)`

### Bibliography Examples

1.  Journal article\
    `ABDULLAH, C. L. HENRIQUEZ, F. MEHMOOD, I. SHAHZADI, Z. ALI, M. T. WAHEED, T. B. CROAT, P. POCZAI, and I. AHMED. 2020. Comparison of Chloroplast Genomes among Species of Unisexual and Bisexual Clades of the Monocot Family Araceae. Plants. 9(6): 737.`

2.  Book section\
    `CHAO, A. and C. CHIU. 2016. Nonparametric Estimation and Comparison of Species Richness. Encyclopedia of Life Sciences. Wiley. 1-11.`

3.  Webpage\
    `GLOBAL BIODIVERSITY INFORMATION FACILITY. 2024. GBIF. Global Biodiversity Information Facility. https://www.gbif.org/ (accessed September 24, 2024).`

4.  Thesis\
    `GRAYUM, M. H. 1984. PALYNOLOGY AND PHYLOGENY OF THE ARACEAE. [Ph.D.]. University of Massachusetts Amherst.`

5.  Book\
    `MAYO, S. J., JOSEF BOGNER, and P. C. BOYCE. 1997. The Genera of Araceae. Royal Botanic Gardens, Kew.`

6.  Software\
    `R CORE TEAM. 2020. R: A Language and Environment for Statistical Computing.`

## Zotero Data Entry Tips

-   Scientific names in titles: wrap Latin names with HTML italics tags in Zotero, for example: `(<i>Rusa marianna</i>)`
-   Theses/dissertations: set the correct degree type in Zotero (for example: `Master's thesis`, `Ph.D. dissertation`)
-   Webpages: fill in the `Accessed` date so retrieval dates appear correctly

## Word Spacing Fix (if needed)

If Microsoft Word forces double spacing inside each reference entry, edit Word's bibliography style:

1.  Go to `Home > Styles` pane.
2.  Modify the bibliography style used by Zotero.
3.  Set line spacing to `Single`.
4.  Set paragraph spacing `After` to `12 pt`.
