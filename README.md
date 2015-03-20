# StateSAIDI2013
Data, methodology, and code behind, "IE Questions: How Long Is Your Blackout?"

This repository includes the analyzed data and behind the story, ["IE Questions: How Long Is Your Blackout?"]().

File Directory:
*  SAIDI SAIFI Analysis 2013.ipynb is an IPython notebook containing the code used to calculate state SAIDI averages with and without major event days. [View it here.](http://nbviewer.ipython.org/gist/jwirfs-brock/ce59704a2f0eac608981)
*  states_2013_SAIDI_with_med.csv contains, for each U.S. state and DC, the sum of electricity customers, sum of total power interruptions in minutes (with major event days), and state average minutes without power (with major event days). (It also includes the sum of the individual utility SAIDIs with major event days in that state.)
*  states_2013_SAIDI_without_med.csv contains, for each U.S. state and DC, the sum of electricity customers, sum of total power interruptions in minutes (without major event days), and state average minutes without power (without major event days). (It also includes the sum of the individual utility SAIDIs without major event days in that state.)
*  utils_2013_SAIDI_with_med.csv contains, by utility, the name, state, SAIDI with major event days (in minutes), number of customers, and total interruption time (in minutes).
*  utils_2013_SAIDI_without_med.csv contains, by utility, the name, state, SAIDI without major event days (in minutes), number of customers, and total interruption time (in minutes).