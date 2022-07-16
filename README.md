# Perturbation MOPA dominance patterns

Social manipulation experiment to derive social dominance patterns in monk parakeets

We provide the code and data for all the analyses for the manuscript titled "Perturbations of single key individuals are sufficient to trigger group-level shifts in social dominance patterns"

LICENSE: CC BY-NC 4.0

CITATION DOI: 10.5281/zenodo.6847366

DESCRIPTION: We performed three social manipulations where we removed and reintroduced a top-ranked monk parakeet for 8 days each to study whether these perturbations of a key individual were sufficient to trigger a shift in group-level dominance patterns.

CODE: All the code for the analyses in the manuscript are provided in the Rmarkdown file called "Stats_perturbations_MOPA_dominance patterns".

METADATA: The data files are provided in the data folder.

"2021_interactions_bin0-12.csv" contains all the agonistic interaction data:

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
