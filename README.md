# Migration barrier dataset
Dataset of calculated migration barriers over a wide range of electrode and solid electrolyte materials that have been explored for battery applications. The dataset is part of the work, "A literature-derived dataset of migration barriers for quantifying ionic transport in battery materials" by Reshma Devi, Avaneesh Balasubramanian, Keith Butler, and Gopalakrishnan Sai Gautam that is currently under review. A pre-print of the manuscript can be found on [arXiv](https://arxiv.org).

The json file contains the complete data and each entry has 10 keywords. The description for each keyword is as follows

| **S.No** | **Tags**         | **Description**                                               |
|---------:|------------------|---------------------------------------------------------------|
| 1        | jid              | Unique JSON ID                                                |
| 2        | structure_ini    | Initial configuration of the migration path                  |
| 3        | structure_fin    | Final configuration of the migration path                    |
| 4        | target           | Reported *Eₘ*                                                 |
| 5        | formula          | Chemical composition                                          |
| 6        | crystal_class    | The crystal class                                             |
| 7        | sys_name         | A unique system name                                          |
| 8        | space_group      | Space group                                                   |
| 9        | XC               | XC functional used for the NEB calculation in literature      |
| 10       | bibtex           | Citation of the research article in `bibtex` format          |

*Table: Description of each tag associated with the datapoints in the Em dataset.*

In case you use our dataset in your work, we will appreciate a citation to our pre-print that is currently available at [arXiv](https://arxiv.org).
