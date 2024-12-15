<h2> Jails and Voting - Survey Analysis </h2>

This is an assignment using data from The Marshall Project. The data explores survey responses on politics and voting by people incarcerated in jails.

Survey here: https://observablehq.com/@themarshallproject/survey3-summaries-by-jail

I downloaded the relevant files from the observable HQ notebook and renamed them using the naming convention in the question_id, and added _nationwide to the end for nationwide responses (as opposed to facility level responses.)

Questions about and limitations with the data: <br>
--how many people have answered in both surveys? is this the same survey population in both? <br>
--jails with less than 5 responses are suppressed, so must use nationwide tibbles to get nationwide totals <br>
--survey responses are not representative of any jail's full population <br>
--data is not broken down on individual level but aggregated to the level of each jail, preventing me from generating my own cross-tabs <br>
--number of respondents in any given jail to these questions are pretty small, so be cautious about drawing conclusions
