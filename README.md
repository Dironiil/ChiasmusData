# Antimetabole Dataset(s)

This github repository contains an extensive number of salient and non-salient example of antimetabole, accompanied with a list of random sentences that are not antimetabole at all.

## Origin of the data

The salient antimetabole were extracted from various places, including the work of Dr. Marie Dubremetz and Dr. Joakim Nivres on chiasmus detection, the work and direct help of Pr. Randy Harris, the book "Never let a fool kiss you or a kiss fool you" by Dr. Mardy Grothe and various -sometimes serendipitous - findings on the internet. The non-salient antimetaboles were extracted from a subset of the [COCA dataset](https://www.english-corpora.org/coca/). The random sentences were extracted from several datasets from [Data World](https://data.world/): [200k English plaintext jokes](https://data.world/taivop/200-k-english-plaintext-jokes), [un_general_speeches](https://data.world/jmalina/un-general-speeches) and the abstract part of [arXiv STEM scholarly articles](https://data.world/liz-friedman/arxiv-stem-scholarly-articles)

Those antimetabole were gathered by Yohan Meyer and Guillaume Berthomet, with the help of Diana Nurbakova, Jelena Mitrovic and Ramona Kühn.

## Organization and location of the data

The data is organized in json files. Each json file contains a unique list named *data*, in which antimetabole are listed. Each antimetabole has two properties: *text* is the raw text containing the antimetabole and *cats* (for the archive) or *category* (for the currently used datasets) is the category of the antimetabole. In the currently used dataset, this category can either be "antimetabole" or "not_antimetabole".

All the data can be found in the `data` sub-folder.
- The `archive` sub-sub-folder contains older version of the datasets that were deprecated in favor of newer ones. Among it:
  - The `salient.json` file contains only examples of salient antimetabole.
  - Similarly, the `not_salient.json` file contains only examples of non-salient antimetabole.
  - Finally, the `all_antimetabole.json` file is an aggregation of both previous files.
- `antimetabole.json` contains a list of all antimetabole collected.
- `not_antimetabole.json` contains a list of sentences that are NOT antimetabole.
- `dataset.json` is a concatenation of the two above.
