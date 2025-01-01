# Presidential Elections in the United States of America in 2004CE and 2020CE

## Data

An excel spreadsheet *Presidential_Election_Data_2000_to_2024.xlsx* contains national and state election data for election years 2000CE to 2024CE from reputable sources. 
Each election year has its own tab. Then, there is an *Analysis* tab which contains the Voter-vs-Census curve, and calculation of novelty and their distributions for two years of interest, 2004CE and 2020CE. The spreadsheet allows user to vary outlier thresholds to test various election outcomes. Notice that all the methods rely on interpolation, so no predictions are attempted.

## Executive Summary

We analyze national and state specific voter count for novelty, focusing on mid-mandate years, 2004CE and 2020CE, of the turbulent mandates (2000CE-2008CE, or Bush-I and Bush-II; and 2016CE-2024CE, or Trump-I and Biden). We define turbulent mandates using national voter count vs. census data.  We define novelty operator $\hat N$ over a time-series of total national and state voters $\{V_i\}_{i=0,1\cdots}$ as a symmetric second difference operator $N_i = \hat N V_i = \frac12 (V_{i+1}+V_{i-1}) - V_i$ , where i is the index of the election year. Negative values imply excessive votes, while positive values suggest disinterested voters. For 2004CE and 2020CE we find national novelty as -4M(illions of voters) and -13M. We find their census-corrected values as -5M and -11M, respectively. 

    The novelty analysis of the 2004CE election suggests two criteria for identifying outliers: 1., a threshold $\delta_V = 0.3$M; and 2., the novelty has to flip the state election vote, $|R_i - D_i| < \delta_V$, where $V_i = D_i + R_i$, are that state totals for the number of votes in that year for (R)epublicans and (D)emocrats. In 2004CE we identify two states as outliers: Ohio and Florida, which together accounted for  -0.9M novelty votes. We refer to this behavior as anti-novelty: If novelty were subtracted from the republican state winner vote count, the democrat candidate would have won the state.

   The novelty analysis of the 2020CE election using the same outlier threshold, identifies 13 outlier states. We show we can categorize them into three groups: 1., the *battleground* states (Arizona, Georgia, Michigan, and Pennsylvania), which have a total novelty of -1.4M; 2., the *apparently republican* states (Florida, North Carolina, and Texas), which have a total novelty of -2.4M; and 3., the *single-majority* states (R: Ohio; D: California, Illinois, New Jersey, New York, Washington), which have a total novelty of -5.6M. To the first group we refer to as novelty (if novelty were subtracted from the democrat state winner vote count, the republican candidate would have won the state). The  second group demonstrates anti-novelty. The states in the third group exhibit diffuse novelty, meaning that the novelty is insufficient to change the outcome of the state election; rather, this novelty only affects the popular vote count.

## Interpretation

We interpret our findings using correlation between the outlier-states and the politics of the day.
We remark, were these random fluctuations in voter numbers and preferences,
such a correlation would have been unremarkable in magnitude or in political orientation.

**2004CE**: We surmise that if there had been actual voter injection by republicans, in its absence the Democrat challenger, Kerry, would have won the presidential election against the incumbent Republican, Bush.
We recall, at that time Bush needed election victory to continue and expand the war effort against Iraq.

**2020CE**:  We surmise that in the 2020CE elections, the republicans injected votes in both, *apparently republican* and *battleground*, group of states. In the former, it was done to affirm increasingly right-wing leaders, DeSantis in Florida and Abbott in Texas. In the latter, the goal was to secure those states for Trump, but they ultimately failed. Without republican interference in the 2020CE elections Trump would have been soundly defeated with a vote tally of 150 to 388 in favor of Biden. This outcome would have effectively removed Trump from politics. Instead, the actions of republicans played out as a damage control in the *apparently republican* states, while in the *battleground* states they evolved into legal and illegal attacks on national level on victorious democrat challenger, Biden, accusing him and the democrats of election fraud. All these actions paved the way for Trump's reprisal in 2024CE.


