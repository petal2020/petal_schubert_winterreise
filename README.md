# petal_schubert_winterreise
data sets for performance analyses of Franz Schubert’s *Winterreise* (1827)

This repository introduces the data sets created during research on recorded performances of Franz Schubert’s *Winterreise* (1827). It complements the following two articles:

Utz, Christian. 2021. “Exzentrisch geformte Klang-Landschaften. Dimensionen des Zyklischen im Lichte von 106 Tonaufnahmen von Schuberts Winterreise aus dem Zeitraum 1928–2020.” *Zeitschrift der Gesellschaft für Musiktheorie* 18. Special Issue: *Musikalische Interpretation als Analyse. Historische, empirische und analytische Annäherungen an Aufführungsstrategien musikalischer Zyklen*: 341–431. https://doi.org/10.31751/1132

Sprau, Kilian. 2021. “Gemessenes Wandern. Zur performativen Umsetzung von Tempo-Taktart-Korrespondenzen in Schuberts Winterreise.” *Zeitschrift der Gesellschaft für Musiktheorie* 18. Special Issue: *Musikalische Interpretation als Analyse. Historische, empirische und analytische Annäherungen an Aufführungsstrategien musikalischer Zyklen*: 433–478. https://doi.org/10.31751/1133

Tables and diagrams included in Utz 2021 can also be obtained separately from https://phaidra.kug.ac.at/o:121742.

# main content

The data discussed in Utz 2021 refer to 106 different recording of *Winterreise* as detailed in the article's discography (https://storage.gmth.de/zgmth/media/1132/Utz_Winterreise_Tab04Ea.pdf).

## (1) raw data (106 recordings)

The Excel sheet **[Schubert_Winterreise_106_raw-data] (https://github.com/petal2020/petal_schubert_winterreise/blob/main/Schubert_Winterreise_106_raw-data.xlsx)** contains duration measurements and tempo  values of these 106 recordings in **106 separate worksheets**. The tsv-file [Schubert_Winterreise_Duhan_Foll_1928_raw-data] (https://github.com/petal2020/petal_schubert_winterreise/blob/main/Schubert_Winterreise_Duhan_Foll_1928_raw-data.tsv) serves as an example demonstrating the structure of these worksheets:
--**column U** contains 76 measure points in the sound file that mark the beginning, the end, and one, or in one case (no. 11), five, intermediary points (see note 84 of the article for an explanation, https://www.gmth.de/zeitschrift/artikel/1132.aspx#fn_ref_84). 
--**columns V, X, and Z** uses these points to calculate the durations of a beginning section (dur begin), the full duration of each song (dur full), and the total duration (dur total) of each song with no. 11 separated into three sub-durations, according to the three tempo zones.
--**column F** provides an initial tempo by calculating the mean tempo of the beginning section.
--**column G** provides the mean tempo over the full duration.
--**column H** calculated the tempo range by expressing the difference between initial tempo and main tempo as a percentage of the main tempo.

## (2) duration, percentage, and tempo tables (106 recordings)

The Excel sheet **[Schubert_Winterreise_106_data] (https://github.com/petal2020/petal_schubert_winterreise/blob/main/Schubert_Winterreise_106_data.xlsx)** contains tables summarizing song durations (dur), the percentage of each song of the full duration of the respective recording (perc) (**Worksheet 1: dur+perc**), the initial tempo of each song (tpo), the tempo range of each song (see (1)), and the tempo variability of each recording which is defined as the mean value of the 24 absolute values of temo range (**Worksheet 2: tpo+tpo-var+tpo-range**). The data of both worksheets are also provided as tsv-files [Schubert_Winterreise_106_dur-perc] (https://github.com/petal2020/petal_schubert_winterreise/blob/main/Schubert_Winterreise_106_dur-perc.tsv) and [Schubert_Winterreise_106_tpo-var] (https://github.com/petal2020/petal_schubert_winterreise/blob/main/Schubert_Winterreise_106_tpo-var.tsv).

## (3) tempo table (64 recordings)

In the additional tsv-file [Schubert_Winterreise_64_tpo.tsv](https://github.com/petal2020/petal_schubert_winterreise/blob/main/Schubert_Winterreise_64_tpo.tsv) a table of initial tempi for the subgroup of 64 recordings discussed in Sprau 2021 is provided.
