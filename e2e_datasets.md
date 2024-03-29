## End-to-End datasets

### English datasets

**NB:** This list is not exhaustive as main aim of the review are multilingual datasets.  We invite additions of other English datasets into this table.

| Dataset      | Task                                                                             | Language | Domain                                              | Size (dialogues) | Comments      | Paper | Dataset |
|--------------|----------------------------------------------------------------------------------|----------|-----------------------------------------------------|------------------|---------------|-------|---------|
| MultiWOZ 2.0    | end-to-end, dialogue state tracking, slot extraction                             | en       | 7 domains, including  restaurant, taxi              | 10438            | H2H           |  [Budzianowski et al.,  2018](https://arxiv.org/abs/1810.00278)    |    [Dataset](http://dialogue.mi.eng.cam.ac.uk/index.php/corpus/)     |
| Taskmaster-1 | end-to-end                                                                       | en       | 6 domains  including ordering pizza,  movie tickets | 7708             | Self-dialogue |   [Byrne et al., 2019](https://arxiv.org/abs/1909.05358)    |    [Dataset](https://research.google/tools/datasets/taskmaster-1/)     |
| MultiDoGo    | end-to-end, intent classification, slot extraction, dialogue acts classification | en       | 6 domains  including airline,  software             | 40576            | H2H           |   [Peskov et al., 2019](https://www.aclweb.org/anthology/D19-1460/)    |   [Dataset](https://github.com/awslabs/multi-domain-goal-oriented-dialogues-dataset)      |

### Monolingual non-English datasets

| Dataset       | Task                                  | Language | Domain                                             | Size (dialogues) | Comments                                                         | Paper | Dataset |
|---------------|---------------------------------------|----------|----------------------------------------------------|------------------|------------------------------------------------------------------|-------|---------|
| CrossWOZ      | dialogue state  tracking,  end-to-end | zh       | 5 domains  including attraction, hotel, taxi       | 6012             | H2H                                                              |    [Zhu et al., 2020](https://arxiv.org/abs/2002.11893)   |    [Dataset](https://github.com/thu-coai/CrossWOZ)     |
| RiSAWOZ       | dialogue state  tracking,  end-to-end | zh       | 12 domains including  education, car,  hospitality | 11200            | H2H                                                              |    [Quan et al., 2020](https://arxiv.org/abs/2010.08738)   |     [Dataset](https://github.com/terryqj0107/RiSAWOZ)    |
| DuConv        | end-to-end                            | zh       | chit-chat                                          | >1 mln*          | H2H;  web-scraped from social network                            |     [Wu et al., 2017](https://www.aclweb.org/anthology/P17-1046/)  |   [Dataset](https://github.com/MarkWuNLP/MultiTurnResponseSelection)      |
| KdConv        | end-to-end                            | zh       | chit-chat  about films, music,  travel             | 4500             | H2H; using an external  knowledge  base                          |   [Zhou et al., 2020](https://arxiv.org/abs/2004.04100)    |     [Dataset](https://github.com/thu-coai/KdConv)    |
| WMT 2020 Chat | end-to-end                            | de       | 6 domains including ordering pizza, movie tickets  | 692              | H2H; translated  from Taskmaster-1; part of WMT 2020  challenge; |  not available yet     |    [Dataset](http://www.statmt.org/wmt20/chat-task.html)     |


### Multilingual datasets

| Dataset  | Task       | Languages                  | Domain                    | Size (dialogues)                                                       | Comments                                           | Paper | Dataset |
|----------|------------|----------------------------|---------------------------|------------------------------------------------------------------------|----------------------------------------------------|-------|---------|
| BiToD | end-to-end | en, zh | Attraction, Hotel, Restaurant, Weather, Metro | 3689 [en], 3543 [zh] | M2M + paraphrase | [ Lin et al., 2021](https://arxiv.org/pdf/2106.02787.pdf)  |  [Dataset](https://github.com/HLTCHKUST/BiToD)  |
| XPersona | end-to-end | en, it, fr, id, zh, ko, ja | chit-chat (persona chats) | 19893[en] 17158[it] 17375[fr] 17846[id] 17322[zh] 17477[ko] 17428[[ja] | H2H;  automatically translated  from [ConvAI2](https://arxiv.org/abs/1902.00098) (dataset [here](https://parl.ai/projects/convai2/)) |   [Lin et al., 2020](https://arxiv.org/abs/2003.07568)    |    [Dataset](https://github.com/HLTCHKUST/Xpersona)     |
| Gutenberg Dialogue Dataset | end-to-end | en, de, nl, es, it, hu, pt | chit-chat (dialogues from books) | 2.5mln[en] 43440[de] 23541[nl] 6912[es] 6664[it] 2826[hu] 2233[[pt] | automatically extracted from books |   [Czaky and Recski, 2021](https://arxiv.org/abs/2004.12752)    |    [Dataset](https://github.com/ricsinaruto/gutenberg-dialog)     |
