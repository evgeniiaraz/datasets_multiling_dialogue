## NLU datasets

#### English datasets

**NB:** This list is not exhaustive as main aim of the review are multilingual datasets.  We invite additions of other English datasets into this table.

| Dataset       | Task                                     | Language | Domains                                            | Size  | N intents | N slots | Paper | Link |
|---------------|------------------------------------------|----------|----------------------------------------------------|-------|-----------|---------|-------|------|
| Banking-77    | intent classification                    | en       | banking                                            | 13083 | 77        | N/A     |   [Casanueva et al., 2020](https://arxiv.org/abs/2003.04807)    |  [Dataset](https://github.com/PolyAI-LDN/task-specific-datasets/tree/master/banking_data)    |
| CLINC-150     | intent classification                    | en       | 10 domains, including banking, work, travel        | 23700 | 150       | N/A     |    [Larson et al., 2019](https://arxiv.org/abs/1909.02027)   |  [Dataset](https://github.com/clinc/oos-eval)    |
| HWU-64        | intent classification, entity extraction | en       | 21 domain,  including  music, news, calendar       | 25716 | 64        | 54      |   [Liu et al., 2019](https://arxiv.org/pdf/1903.05566.pdf)    |   [Dataset](https://github.com/xliuhw/NLU-Evaluation-Data)   |
| Restaurants-8K | slot extraction                          | en       | restaurant booking                                 | 11929 | N/A       | 5       |    [Coope et al., 2020](https://arxiv.org/abs/2005.08866)   |   [Dataset](https://github.com/PolyAI-LDN/task-specific-datasets/tree/master/span_extraction/restaurant8k)   |
| Snips         | intent classification, slot extraction   | en       | 7 domains,  including  music, weather,  restaurant | 14484 | 7         | 39      |  [Coucke et al., 2018](https://arxiv.org/abs/1805.10190)     |   [Dataset](https://github.com/sonos/nlu-benchmark)   |
| ATIS          | intent classification, slot extraction   | en       | airline travels                                    | 5871  | 21        | 120     |   [Price, 1990](https://www.aclweb.org/anthology/H90-1020.pdf)    |       |


#### Monolingual non-English datasets

| Dataset      | Task                                       | Language | Domains                                           | Size  | # intents | # slots | Paper | Link |
|--------------|--------------------------------------------|----------|---------------------------------------------------|-------|-----------|---------|-------|------|
| MEDIA        | slot extraction                            | fr       | hotel  reservation                                | 15000 | N/A       | 83      |    [Bonneau-Maynard et al., 2005](https://www.isca-speech.org/archive/archive_papers/interspeech_2005/i05_3457.pdf)   |      |
| SLU-IT       | intent classification, slot extraction     | it       | 7 domains,  including  music, weather, restaurant | 7142  | 7         | 39      |   [Castellucci et al., 2019](https://arxiv.org/abs/1907.02884)    |      |
| Almawave-SLU | intent classification,  slot extraction    | it       | 7 domains,  including  music, weather, restaurant | 14484 | 7         | 39      |    [Bellomaria et al., 2019](https://arxiv.org/abs/1907.07526)   |   Available by email to authors   |
|      [Zhang et al., 2017](https://arxiv.org/abs/1709.10217)        | intent classification                      | zh       | combination of chit-chat and task-oriented        | 4000  | 31        | N/A     |   [Zhang et al., 2017](https://arxiv.org/abs/1709.10217)    |  [Dataset](https://github.com/WindInWillows/SMP2018-ECDT-TASK1)    |
| ECSA dataset | slot extraction,  named entity recognition | zh       | online commerce                                   | 27615 | N/A       | N/A*    |       |      |
| Chinese ATIS | intent classification, slot extraction     | zh       | airline travels                                   | 5871  | 21        | 120     |   [He et al., 2013](https://ieeexplore.ieee.org/abstract/document/6639292)    |      |

<div align="center">* Slots are annotated with sequence tags showing where a slot starts and ends.</div>


