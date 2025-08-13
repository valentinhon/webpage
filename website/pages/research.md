---
title: Valentin Honore's webpage
author: Valentin Honoré
shortbio: Associate Professor (Maître de Conférences) at ensIIE
description-meta: Associate Professor (Maître de Conférences) at ensIIE
og-url: https://webpage.github.io
location: Evry - ensIIE (Office 242) & Télécom SudParis/Samovar (Office C404)
email: valentin.honore@ensiie.fr
phone: 01.69.36.73.35
picture: img/profile.png
picture-round: false
side-by-side: true
pronouns: He/him
og-picture: https://basicpage.github.io/img/profile.png
orcid: 0000-0003-1028-5719
dblp: https://dblp.org/pid/248/5108.html
scholar: https://scholar.google.com/citations?user=AwYK-44AAAAJ&hl=fr
github: valentinhon
gitlab: vhonore
linkedin: https://www.linkedin.com/in/valentin-honore-334693100/
footer: >-
  Based on the
  [basicpage template](https://github.com/basicpage/basicpage.github.io),
  made to be easy to use! 🎓
---


# PhD Students Supervision

- **[Catherine GUELQUE](https://wiki.khatharsis.com/)**, with [François TRAHAY](https://trahay.wp.imtbs-tsp.eu/) (Nov. 23 - Oct. 26): [HPC trace analysis at scale](https://theses.fr/s374880?domaine=theses)



# Research Interests

I am interested in various scheduling and resource partitioning problems related to high performance computing (HPC) and large-scale storage systems.

I am interested in optimizing the execution of applications, and understand the problems application users face when running their code on large-scale platforms.
I mix theoretical studies and experimentation to design models and approximation algorithms in order to propose cost-efficient scheduling strategies for various types of applications.

Since 2023, I am working on performance analysis for large-scale applications in the PEPR [NumPEx](https://numpex.org/fr/) project.

In addition, I also work on large-scale storage, in particular on how to efficiently use magnetic tape storage.
Do not hesitate to contact me if you want to collaborate or discuss on these topics!!

<span style="font-size:22px;padding:10px;background-color:#ff0000">
!!! NEWS !!!
</span>


<span style="padding:10px;background-color:#f0f0f0">
The VHS project has been funded by the <a href="https://anr.fr/fileadmin/aap/2025/selection/aapg-2025-selection.pdf">ANR JCJC program</a> for the AAPG 2025 project call.
See the dedicated webpage of the project <a href="vhs.html">here</a>.
</span>


# Post-doc ([CC-IN2P3](https://cc.in2p3.fr/), CNRS)

## Trustful Simulation of High-performance Workflows

I extended my PhD work on performance evaluation of *in situ* processing, where simulation and analytics are co-scheduled on the same computing resources. Determining the best allocation, i.e, how many resources to allocate to each component of an *in situ* workflow; and mapping, i.e, where and at which frequency to run the data analytics component, is a complex task for which I proposed performance models during my PhD. However, performance assessment of such solutions is crucial to the efficient execution of *in situ* workflows.

In this project, I developed [SimSitu](https://figshare.com/articles/online_resource/Reproducibility_Artifact_for_the_paper_SIM-SITU_A_Framework_for_the_Faithful_Simulation_of_in_situ_Processing_/20416008?file=36503601), a faithful simulation framework based on the [SimGrid](https://simgrid.org/) toolkit. SimGrid is capable of accurately simulating distributed applications running on parallel machines. This work was done in collaboration with Oak Ridge National Laboratory (USA) and the University of Southern California (USA). A resulting publication was selected for publication in [e-Science'22](https://cnrs.hal.science/hal-03504863v2).

## Scheduling User Requests on Magnetic Tapes

The second research direction of my postdoc concerns the scheduling of user requests on magnetic tapes. Magnetic tape is a high-capacity storage technology that is still widely used in computing and data centers to store cold data. When accessing data on tapes, deciding the ordering of the user requests on a tape is crucial to improve the quality of service experienced by users of tape storage systems. In this work, we proposed an exact algorithm for the open problem of minimizing the average service time for read requests on a magnetic tape considered as linear. A resulting paper was accepted for publication in [ICAPS'22](https://cnrs.hal.science/hal-03482022).

In addition, we also publicly released a [dataset](https://figshare.com/s/a77d6b2687ab69416557) of tape descriptions and associated user requests extracted from execution logs from the IN2P3 computing center.


# PhD (Inria, [TADaaM](https://team.inria.fr/tadaam/) team)

My PhD focused on resource partitioning, design of scheduling strategies as so as data movement in HPC applications.

I worked on two complementary research directions.

In the first direction, I was interested in modeling and studying *in situ* processing, where simulation and analytics are done in parallel to avoid I/O congestion. This work was done in collaboration with [Bruno Raffin](http://datamove.imag.fr/bruno.raffin/), and our results were published in [IJHPCA](https://hal.inria.fr/hal-02091340/) journal.

The second direction was  scheduling problems for stochastic applications, for instance Neuroscience applications. The goal was to propose optimal scheduling strategies for single-core stochastic application running on a reservation-based platform. Stochastic jobs are jobs whose execution time cannot be determined easily, mostly because they are input-dependent. They arise from the heterogeneous, dynamic and data-intensive requirements of new emerging fields such as neurosciences. I spent two months in Vanderbilt University, Nashville, USA working on this topic in the group of Padma Raghavan. Two papers on these topics were published in [IPDPS'19](https://hal.inria.fr/hal-01968419/), [IPDPS'20](https://hal.inria.fr/hal-02448393/), and a journal paper in [IEEE Transactions on Parallel and Distributed System](https://hal.inria.fr/hal-03010676v1/).


# [Return to main page](https://valentinhon.github.io/webpage/)
