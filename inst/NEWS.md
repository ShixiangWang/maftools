# CHANGES IN VERSION 2.4.00
## BUG FIXES

- `lollipopPlot2` error with zero mutation Issue: [#480](https://github.com/PoisonAlien/maftools/issues/480)
- `inferHeterogeneity` PR [#473](https://github.com/PoisonAlien/maftools/issues/473)
- `oncoplot` cnv crosses border [#472](https://github.com/PoisonAlien/maftools/issues/472)
- Avoid wrongly naming columns in `annovarToMaf` Issue: [#457](https://github.com/PoisonAlien/maftools/issues/457)
- Duplicated color code Issue: [#452](https://github.com/PoisonAlien/maftools/issues/452)
- oncoplot with exprsTbl leads to wrong alignment Issue: [#451](https://github.com/PoisonAlien/maftools/issues/451)
- plotMafSummary with single sample Issue: [#449](https://github.com/PoisonAlien/maftools/issues/449)
- Avoid empty spaces and quoates while reading funcotator MAF Issue: [#403](https://github.com/PoisonAlien/maftools/issues/403) [#397](https://github.com/PoisonAlien/maftools/issues/397)

## ENHANCEMENTS

- `OncogenicPathways` improvements Issue: [#505](https://github.com/PoisonAlien/maftools/pull/509)
- Added `showSum`, `colNC`, `nShiftSymbols`, `sigSymbolsSize`, `sigSymbolsFontSize`, `pvSymbols` arguments to `somaticInteractions` PR: [#505](https://github.com/PoisonAlien/maftools/pull/505) Thanks [zmiimz](https://github.com/zmiimz)
- Added `anno_height`, `drawBox`, `drawExtraBar` arguments to `oncoplot` PR: [#501](https://github.com/PoisonAlien/maftools/pull/501) Thanks [Kai Gu](https://github.com/kaigu1990)
- Added `decreasing` argument to `tcgaComapre` Issue: [#497](https://github.com/PoisonAlien/maftools/issues/497)
- Added startgain and startlost to `annovarToMaf` Issue: [#487](https://github.com/PoisonAlien/maftools/issues/487)
- `y_lims` argument in gisticChromPlot Issue: [#485](https://github.com/PoisonAlien/maftools/issues/485)
- Added support for highlighting multiple additionalFeatures Issue: [#476](https://github.com/PoisonAlien/maftools/issues/476)
- Pairwise t-test and mutational load in `tcgaCompare` Issue: [#453](https://github.com/PoisonAlien/maftools/issues/453)
- Added `titleText` argument to `oncoplot` Issue: [#448](https://github.com/PoisonAlien/maftools/issues/448)
- Highlight mutated genes on gisticChromplot Issue: [#443](https://github.com/PoisonAlien/maftools/issues/443)
- Added `legend_height` argument to `oncoplot` Issue: [#346](https://github.com/PoisonAlien/maftools/issues/346)
- Added `bgBorderCol` `domainBorderCol` `showLegend` argument to `lollipopPlot`

## NEW FUNCTIONS AND FEATURES

- `tmb` Simple tumor mutation burden estimation function.
- `setdiffMAF` and `intersectMAF`. Set operations for MAF files. PR: [#508](https://github.com/PoisonAlien/maftools/pull/508) Thanks [Shixiang Wang](https://github.com/ShixiangWang)
- `tcgaDriverBP` Compare genes to known TCGA drivers and their biological pathways
- `vafCompare` plots vaf distribution of target genes from two cohorts Issue: [#495](https://github.com/PoisonAlien/maftools/issues/495)
- `coBarplot` side-by-side barplot for maf comparison Issue: [#486](https://github.com/PoisonAlien/maftools/issues/486)
- Group genes in `oncoplot` by specific pathways. This can be done by setting `pathways = 'auto'` or by providing a two column data.frame/tsv-file with Gene names and their corresponding pathway belongings.
- Oncoplot gains `rightBarData` and `leftBarData` arguments for user specific side bar plots.
- Default flatUI colors for lollipop plots

## Deprecated
- `geneCloud` and `pancanComparison`