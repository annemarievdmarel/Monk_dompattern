# Perturbation MOPA dominance patterns

Social manipulation experiment to derive social dominance patterns in monk parakeets

We provide the code and data for all the analyses for the manuscript titled "Social manipulations trigger shifts in group-level dominance patterns" (*EcoEvoRxiv* <https://doi.org/10.32942/osf.io/9qyb2>)

LICENSE: CC BY-NC 4.0

CITATION DOI: 10.5281/zenodo.6847366

DESCRIPTION: To investigate factors affecting dominance patterns, we experimentally manipulated captive groups of monk parakeets (*Myiopsitta monachus*) using targeted perturbations to cause social instability through rank-based removals and reintroductions of group members across three study years (2020-2022).

CODE: All the code for the analyses in the manuscript are provided in the Rmarkdown files. The first code files are the "stats_perturbations_MOPA_dominance patterns\_[year].Rmd" to summarize the interaction files and obtain the dominance patterns, which are used for further analyses, such as "dompatterns_analysis_perturbations.Rmd" for the dominance pattern comparisons, "Stats_aggression dynamics.Rmd" for the aggression balance, and "Stats_aggression networks.Rmd" for the visualisation of aggression networks.

METADATA: The output folder contains the summarized aggression by dyad and by assessment period files ("dyad.aggXbin.[fieldseason].csv"), the power score, and the dominance pattern files.

The data files are provided in the data folder. For example, to obtain the dyad output files for the 2021 field season, the following files are necessary:

"2021_interactions_bin0-12.csv" contains all the agonistic interaction data

-   sessionKEY = date and observer,
-   session_start_timeStamp = date and time observation session started
-   date = date of when interaction took place,
-   time = time that interaction took place
-   actor = aggressor
-   subject = receiver of aggression
-   behavior = interaction type (either crowds or displace)
-   type = experimental period
-   bin = interaction data is compiled into 3-day bins during the experiment

"2021_birdIDs.csv" contains the individual information for each monk parakeet used in the experiment.

-   band_id = unique band number

-   sex = male of female

-   year_captured = the year the birds were captured from Southern Florida

-   site_captured = birds were trapped in 4 different feral populations

-   mark_id = unique color code combination (B = blue/ G = Green / P = Purple / O = Orange)

"2021_3daybins.csv" contains the dates and the rank assessment periods

-   date = year-month-day

-   perturbation = explains at what part of the experiment we are on

-   type = the perturbation type (removal or reintroduction)

-   bin = unique number for the 3-days to obtain rank and dominance pattern

-   n_birds = total number of birds in the group

-   capture = the number of the capture event

-   capture_date = date of capture

-   rank_assessment = the 3-days bins used for rank assessment in the paper

"2021_observation hours_cleaned.csv" contains the information of the number of observation hours

-   date = year-month-day

-   type = type of hours calculated (obs = observations & breaks = breaks

-   breaks = the number of breaks per observer per day

-   subject = the subject of the breaks (e.g., lunch break) or the observer's name that took a break

-   start = the start time of the observation or break in hour:min format

-   end = the end time of the observation or break in hour:min format

-   start_time = the start time of the observation or break in hour:min:s format

-   end_time = the end time of the observation or break in hour:min:s format

-   totaltime = duration of the period in seconds and hours

-   totaltime_min = duration of the period in minutes

-   totaltime_hours = duration of the period in hours
