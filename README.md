# How does Journal Ranking change when measuring in-text citations rather than citaitons?

This repo asks how Journal Ranking changes when measuring in-text citations rather than citations.
In-text citations may be a better indicator of whether a paper has been engaged with since the number of in-text citations is a count for how much that paper is used. In a simple case, a paper cited once in-text might be a perfunctory citation while a paper cited more than once in-text might be a more significant citation such as one used to justify chosen methods.

In order to look at the effect of using in-text citations in bibliometrics, we look at a popular operationalization of measuring citations, Journal Ranking. Specifically, we look at the Journal Impact Factor which is defined as the number of citations recieved in a particular year by publications from the previous two years, those citations are normalized by the total number of publications in the previous two years.

We use scite.ai data to access the in-text citations to these publications.
This data is available in `./data/ranking_2019_with_subject_and_oa.csv` which also contains subject and OA status.
We perform the following analysis in order to show how Journal Ranking might change when measuring in-text citations rather than citations.

The experiments for this are listed in ./Experiments.ipynb
