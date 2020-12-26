## NLU datasets

### English datasets

**NB:** This list is not exhaustive as main aim of the review are multilingual datasets.  We invite additions of other English datasets into this table.

| Dataset       | Task                                     | Language | Domains                                            | Size  | N intents | N slots | Paper | Link |
|---------------|------------------------------------------|----------|----------------------------------------------------|-------|-----------|---------|-------|------|
| Banking-77    | intent classification                    | en       | banking                                            | 13083 | 77        | N/A     |   [Casanueva et al., 2020](https://arxiv.org/abs/2003.04807)    |  [Dataset](https://github.com/PolyAI-LDN/task-specific-datasets/tree/master/banking_data)    |
| CLINC-150     | intent classification                    | en       | 10 domains, including banking, work, travel        | 23700 | 150       | N/A     |    [Larson et al., 2019](https://arxiv.org/abs/1909.02027)   |  [Dataset](https://github.com/clinc/oos-eval)    |
| HWU-64        | intent classification, entity extraction | en       | 21 domain,  including  music, news, calendar       | 25716 | 64        | 54      |   [Liu et al., 2019](https://arxiv.org/pdf/1903.05566.pdf)    |   [Dataset](https://github.com/xliuhw/NLU-Evaluation-Data)   |
| Restaurants-8K | slot extraction                          | en       | restaurant booking                                 | 11929 | N/A       | 5       |    [Coope et al., 2020](https://arxiv.org/abs/2005.08866)   |   [Dataset](https://github.com/PolyAI-LDN/task-specific-datasets/tree/master/span_extraction/restaurant8k)   |
| Snips         | intent classification, slot extraction   | en       | 7 domains,  including  music, weather,  restaurant | 14484 | 7         | 39      |  [Coucke et al., 2018](https://arxiv.org/abs/1805.10190)     |   [Dataset](https://github.com/sonos/nlu-benchmark)   |
| ATIS          | intent classification, slot extraction   | en       | airline travels                                    | 5871  | 21        | 120     |   [Price, 1990](https://www.aclweb.org/anthology/H90-1020.pdf)    |       |


### Monolingual non-English datasets

| Dataset      | Task                                       | Language | Domains                                           | Size  | # intents | # slots | Paper | Link |
|--------------|--------------------------------------------|----------|---------------------------------------------------|-------|-----------|---------|-------|------|
| MEDIA        | slot extraction                            | fr       | hotel  reservation                                | 15000 | N/A       | 83      |    [Bonneau-Maynard et al., 2005](https://www.isca-speech.org/archive/archive_papers/interspeech_2005/i05_3457.pdf)   |      |
| SLU-IT       | intent classification, slot extraction     | it       | 7 domains,  including  music, weather, restaurant | 7142  | 7         | 39      |   [Castellucci et al., 2019](https://arxiv.org/abs/1907.02884)    |      |
| Almawave-SLU | intent classification,  slot extraction    | it       | 7 domains,  including  music, weather, restaurant | 14484 | 7         | 39      |    [Bellomaria et al., 2019](https://arxiv.org/abs/1907.07526)   |   Available by email to authors   |
|      [Zhang et al., 2017](https://arxiv.org/abs/1709.10217)        | intent classification                      | zh       | combination of chit-chat and task-oriented        | 4000  | 31        | N/A     |   [Zhang et al., 2017](https://arxiv.org/abs/1709.10217)    |  [Dataset](https://github.com/WindInWillows/SMP2018-ECDT-TASK1)    |
| ECSA dataset | slot extraction,  named entity recognition | zh       | online commerce                                   | 27615 | N/A       | N/A<a href="#note1" id="note1ref"><sup>1</sup></a>    |   [Gong et al., 2019](https://arxiv.org/abs/1803.11326)    |   [Dataset](https://drive.google.com/drive/folders/1wRR4oCmYumA7TXMcQtQxvT8vaJIZMus-)   |
| Chinese ATIS | intent classification, slot extraction     | zh       | airline travels                                   | 5871  | 21        | 120     |   [He et al., 2013](https://ieeexplore.ieee.org/abstract/document/6639292)    |      |

<a id="note1" href="#note1ref"><sup>1</sup></a>Slots are annotated with sequence tags showing where a slot starts and ends.

<div align="center">* Slots are annotated with sequence tags showing where a slot starts and ends.</div>

### Multilingual datasets

| Dataset                         | Task                                    | Languages                          | Domains                                       | Size                                                       | # intents                                    | # slots                                          | Paper | Link |
|---------------------------------|-----------------------------------------|------------------------------------|-----------------------------------------------|------------------------------------------------------------|----------------------------------------------|--------------------------------------------------|-------|------|
| Multilingual TOP                | intent classification, slot extraction  | en, es, th                         | alarm, reminder, weather                      | 43323[en]<br>8643[es]<br>5082[th]                             | 12                                           | 11                                               |  [Schuster et al., 2019](https://arxiv.org/abs/1810.13327)     |  [Dataset](https://fb.me/multilingual_task_oriented_data)    |
| ATIS in Chinese  and Indonesian | slot extraction                         | en, zh, id                         | airline travels                               | 7381                                                       | N/A                                          | 120**                                            |    [Susanto and Lu, 2017](https://www.aclweb.org/anthology/P17-2007.pdf)   |   [Dataset](https://drive.google.com/file/d/0B6hvU8RdMvlWQ3ZaV3RYYXVpaTQ/view)   |
| Multilingual ATIS               | intent classification, slot extraction  | en, hi, tr                         | airline travels                               | 1493[hi]<br>1316[tr]                                        | 21                                           | 120                                              |     [Upadhyay et al., 2018](https://ieeexplore.ieee.org/document/8461905)  |   [Dataset](https://catalog.ldc.upenn.edu/LDC2019T04)   |
| MultiATIS++                     | intent classification, slot extraction  | en, es, pt, <br>de, fr, zh, <br>ja, hi, tr | airline travels                               | 5871<br> 2493[hi] <br>1353[tr]     | 18<br> 17[hi,tr] | 84<br>75[hi] <br>71[tr] |   [Xu et al., 2020](https://arxiv.org/abs/2004.14353)    |   Available by email to authors; will be in LDC;   |
| MTOP                            | intent classification*, slot extraction | en, de, fr,<br>es, hi, tr             | 11 domains,<br>  including<br>  music, news,<br>  recipes | 18788[en,th]<br>16585[de]<br>16182[es]<br>15459[fr]<br>15195[hi] | 117                                          | 78                                               |     [Li et al., 2020](https://arxiv.org/abs/2008.09335)  | [Dataset](https://fb.me/mtop_dataset)     |

