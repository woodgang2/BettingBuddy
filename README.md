Ever wondered which collegiate baseball teams are the strongest? It's a simple question, right? I mean, if you look up "top college baseball teams", you get a handy list of 25 teams considered to be the best teams.

The core issue with the official rankings is that they are highly subjective - the best teams rarely play each other over the course of the Spring season, usually running up scores against teams which never stood a chance. Even when they do, baseball is notoriously susceptible to sample size noise. The selection committee takes factors like [RPI] (https://en.wikipedia.org/wiki/Rating_percentage_index) into account, but RPI has no real statistical underpinning (those familiar with baseball will know, however, that sports people love these handwavy stats *cough* OPS).

Public models for quantifying team strength which delve deeper than the official rankings do exist, but they by and large treat teams as monolithic entities, ignoring the effects of player absences, starting pitchers, and reliever fatigue. The ELO framework was used for this project because player modifications can be easily baked in, but custom calculations were necessary to more accurately represent the information gain in individual collegiate games. The project outperformed the Glicko-2 system, random forest approaches, and some simple RL implementations trained over the post-2000 dataset.
