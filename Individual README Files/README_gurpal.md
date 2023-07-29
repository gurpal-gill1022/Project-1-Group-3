project-1-group-3 - Housing Prices in Toronto

This section of the project was completed by Gurpal Gill with feedback provided from each of his team members. 

The raw dataset consisted of all different locations in the Greater Toronto Region with index, benchmark and YOY changes from different types of homes (single family, townhomes and apartments). For simplicity, the composite benchmark and YOY changes were only used as the benchmark accounted for all types of homes and being assigned to a single value. The data cleanup process included filtering locations to Toronto-related areas only, assigning each location to its corresponding district, replacing the entire date to year only, and filtering down to the District, Year, CompBenchmark and CompYOYChange columns. 

In the analysis part, we separated the data into each District and calculated the averages of CompBenchmark and CompYOYChange. These calculations were then organized into a new DataFrame which was sorted by Year and District. Finally, the data was then visualized in two plot graphs which illustrate the Average Price of Homes in Toronto per District and Average YOY Changes per District from 2015 - 2021.