
# SICSS: estimating causal effects of policy interventions
This webpage contains all the materials for a workshop on causal impact assessment. The materials on this website are [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) licensed.

![cc](https://mirrors.creativecommons.org/presskit/icons/cc.svg) ![by](https://mirrors.creativecommons.org/presskit/icons/by.svg)

## Course objectives

How do we assess whether a school policy intervention has had the desired effect on student performance? How do we estimate the impact a natural disaster has had on the inhabitants of affected regions? How can we determine whether a change in the maximum speed on highways has lead to fewer accidents? These types of questions are at the core of many social scientific research problems. While questions with this structure are seemingly simple, their _causal effects_ are notoriously hard to estimate, because often we cannot perform a randomized controlled experiment. 

In this session, we will deal with several advanced methods for answering such questions, with a dual focus:

- What are the causal assumptions underlying these methods?
- How can we put these methods in practice?

At the end of this session, participants have a firm grasp of the basics and limits of causal impact assessment, as well as the skills to start applying these methods in their own work.

## Prerequisites

We assume the following:

- you are comfortable with estimating and interpreting regression models
- you are familiar with the `R` programming language and you have a recent version installed
- it's a bonus if you are somewhat familiar with the `tidyverse` suite of packages (`readr`, `dplyr`, `ggplot`, `tibble`)
- you have installed the following `R` packages on your computer:
  - `tidyverse`
  - `sandwich`
  - `lmtest`
  - `fpp3`
  - `tidysynth`

  You can use the following code to install these at once:
  ```r
  install.packages(c("tidyverse", "sandwich", "lmtest", "fpp3", "tidysynth"))
  ```

## Workshop schedule & materials

See the schedule below. Note that some of the practicals are interrupted by breaks or lunch. We aim to end by 15:00.

| Time  | Duration | Activity     | Content                            | link |
| :---: | :------: | :----------- | :--------------------------------- | :--- |
| 09:00 | 60       | Lecture      | Introduction & causal inference    | [`intro.pdf`](./lectures/01_introduction/intro.pdf) |
| 10:00 | 15       | Break        | Coffee                             |      |
| 10:15 | 45       | Practical    | Data + basic methods               | [`intro.html`](./practicals/01_introduction/intro.html) |
| 11:00 | 45       | Lecture      | Interrupted time series            | [`its.pdf`](./lectures/02_its/its.pdf)    |
| 11:45 | 45       | Practical    | Interrupted time series            | [`its.html`](./practicals/02_its/its.html) |
| 12:00 | 30       | Lunch        | Food                               |      |
| 13:00 | 45       | Lecture      | Synthetic control                  | [`synth.pdf`](./lectures/03_synth/synth.pdf) |
| 13:45 | 30       | Practical    | Synthetic control                  | [`synth.html`](./practicals/03_synth/synth.html) |
| 14:00 | 15       | Break        | Coffee                             |      |
| 14:30 | 30       | Conclusion   | Conclusion + open questions        | [`discussion.pdf`](./lectures/04_discussion/discussion.pdf)    |

You can download the dataset we have prepared from here: [`proposition99.rds`](./data/proposition99.rds). In the first practical, you will save it in a nicely accessible place, as we will be using it in every subsequent practical.

## Additional links

- Course materials for [program evaluation for public service](https://evalsp23.classes.andrewheiss.com/)
- Causal inference for the Brave and True [online python book](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)
- Using Synthetic Controls: Feasibility, Data Requirements, and Methodological Aspects [pdf available here](https://www.aeaweb.org/articles?id=10.1257/jel.20191450)
- Shameless plug: my own [R package `pensynth`](https://github.com/vankesteren/pensynth) for penalized synthetic controls
- Forecasting: principles and practice 3rd ed. [online R book](https://otexts.com/fpp3/)
- Application of causal impact analysis in marketing at [stitch fix](https://multithreaded.stitchfix.com/blog/2016/01/13/market-watch/)

## Contact

This project is developed and maintained by the [ODISSEI Social Data Science (SoDa)](https://odissei-soda.nl/) team.

<img src="https://odissei-soda.nl/images/logos/soda_logo.svg" alt="SoDa logo" width="250px"/> 

For questions about this course, you can contact us at [soda@odissei-data.nl](mailto:soda@odissei-data.nl), or you can contact the instructors Erik-Jan ([e.vankesteren1@uu.nl](mailto:e.vankesteren1@uu.nl)) or Oisín ([ryanoisin@gmail.com](mailto:ryanoisin@gmail.com)) directly.

Course logo created by Nithinan Tatah from Noun Project
