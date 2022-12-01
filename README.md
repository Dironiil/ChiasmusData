# Antimetabole Dataset(s)

## General description

This github repository contains an extensive number of salient and non-salient example of antimetabole. The salient antimetabole were extracted from various places, including the work of Dr. Marie Dubremetz and Dr. Joakim Nivres on chiasmus detection, the work and direct help of Pr. Randy Harris, the book "Never let a fool kiss you or a kiss fool you" by Dr. Mardy Grothe and various -sometimes serendipitous - findings on the internet.

Those antimetabole were gathered by Yohan Meyer and Guillaume Berthomet, with the help of Diana Nurbakova, Jelena Mitrovic and Ramona Kühn.

## Organization and location of the data

The data is organized in json files. Each json file contains a unique list named *data*, in which antimetabole are listed. Each antimetabole has two properties: *text* is the raw text containing the antimetabole and *cats* is the category of the antimetabole. This category can either be "NotSalient", "Antimetabole" or "NestedAntimetabole" (the latter meaning that there is at least three pair of terms organized in a chiastic figure, i.e. A B C C B A).

All the data can be found in the `data` sub-folder.
- The `salient.json` file contains only examples of salient antimetabole.
- Similarly, the `not_salient.json` file contains only examples of non-salient antimetabole.
- Finally, the `all_antimetabole.json` file is an aggregation of both previous files.
