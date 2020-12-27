## Dialogue State Tracking datasets

### English datasets

**NB:** 

1. This list is not exhaustive as main aim of the review are multilingual datasets.  We invite additions of other English datasets into this table.

2. This table includes datasets *only* for dialogue state tracking. The datasets which can also be used to develop end-to-end models will be included in the "End-to-end datasets" section.


| Dataset | Task                    | Language | Domain             | Size (dialogues) | H2M / H2H<a href="#note1" id="note1ref"><sup>1</sup></a> | Paper | Dataset |
|---------|-------------------------|----------|--------------------|------------------|-----------|-------|---------|
| DSTC 1  | dialogue state tracking | en       | bus information    | 15886            | H2M       |  [Raux et al., 2005](https://www.microsoft.com/en-us/research/publication/lets-go-public-taking-spoken-dialog-system-real-world/),  [Williams et al., 2013](https://www.aclweb.org/anthology/W13-4065/)    |     [Dataset](https://www.microsoft.com/en-us/research/event/dialog-state-tracking-challenge/?from=http%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fevents%2Fdstc%2F#!dstc1-downloads)    |
| DSTC 2  | dialogue state tracking | en       | restaurant booking | 3000             | H2M       |   [Henderson et al., 2014]    |    [Dataset](https://github.com/matthen/dstc)     |
| WOZ 2.0 | dialogue state tracking | en       | restaurant booking | 1200             | H2H       |    [Wen et al., 2017](https://arxiv.org/pdf/1604.04562.pdf), [Mrsic t al., 2017](https://arxiv.org/pdf/1606.03777.pdf)   |         |

<a id="note1" href="#note1ref"><sup>1</sup></a> H2M -- human to machine dialogues; H2H -- human to human dialogues.