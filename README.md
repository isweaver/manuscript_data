# mp_mep_retweet_edges_timeseries.zip
This file contains the dataset used to produce the manuscript "Dynamic social media affiliations among UK politicians".

It is in compressed json format with the following fields:

1. `dates` - list of date ranges which serve as labels for lists in token_countsand edges
2. `tokens` - list of tokens which serve as labels for the token_countsfield
3. `token_counts` - list of token counts for each date range in dates, with the format [TOKEN, COUNT]
4. `nodes` - list of nodes which serve as labels for the edgesfield
5. `edges` - list of network edges for each date range in dates, with the format [FROM, TO, WEIGHT]
