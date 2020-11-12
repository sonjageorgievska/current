# Application form for starting/continuing a SIG

## What is/will be the name of the SIG?
<!--  Pick a name that reflects the goal of the SIG.
      Make it specific enough to be meaningful,
      but broad enough to give you room  to shift focus when necessary.  --> GPU Computing SIG

Explanation: I know we said last time we would change the name to “Accelerated Computing SIG”, but GPUs are experiencing a lot of renewed attention currently. For example, with Intel moving into the GPU market and it seems Intel has all but abandoned their attempt of pushing FPGAs into the HPC market. Very recently, the first generation of exascale supercomputers have been announced and all of them are GPU-based systems. In the US 2 exascale supercomputers will be build, one with Intel GPUs one with AMD GPUs, and the EU will build at least two GPU-based (one Nvidia-based and one AMD-based) exascale supercomputers. These developments put new pressure on application developers to develop (performance) portable code that can run on a wide range of different GPUs. In addition, outside of the eScience center ‘Accelerated Computing’ isn’t a very common term, certainly not as well-known as GPU Computing. Because this SIG is quite outward looking as well, it makes sense to use a well-known and well-fitting name, instead of one that might cover all but is too general 90% of the time.

## Which two persons will act as SIG Leads?
Ben van Werkhoven and Alessio Sclocco


## What is SIG’s mission?
Our mission is to enrich the knowledge of our members in the topic of accelerated computing, with a focus on GPUs, and to do so we organize meetings to discuss recent developments in technology and research. We focus on technologies and expertise that are required to accelerate scientific computations, specifically by rewriting and optimizing the compute-intensive parts of the code. There are many currently running projects that require expertise in GPU programming, and also in proposals currently under our calls we see a growing demand for GPU programming expertise at the eScience center.

Furthermore, we maintain close connections with the broad research community by actively participating in national-level workshops, by inviting external speakers at the SIG meetings, and having students present their research projects. We are also involved in the teaching of GPU programming courses, both nationally and internationally and represent the first contact point for eScience engineers having issues with performance-critical code, which happens regularly.

Finally, the eScience Center GPU programming expertise is internationally recognized, which is e.g. proven by our leading role in European projects such as ESIWACE-2. To strengthen this position and secure future participation in large HPC collaborations, our skill in optimizing and accelerating scientific applications is essential and the GPU SIG plays a key role in preserving and improving this expertise.

## What is the GitHub repository of the SIG use?
https://github.com/NLeSC/gpu-sig

## What is the Office group of the SIG use?
GPU Computing

## SIG outcomes in the period April 2020 - October 2020 (for existing SIGs)

We’ve had several presentations from eScience engineers on their projects, where the SIG provides comments and suggestions on the work of the engineers. Ben gave an update about his research plans in auto-tuning, Sagar Dolas (external speaker from SURFsara) gave an update on the new developments in supercomputers, in particular focusing on the recent surge of AMD in the GPU market. Several students from VU/UvA presented the results of their research projects.

Ben van Werkhoven, Willem Jan Palenstijn, and Alessio Sclocco have presented their paper “Lessons learned from a decade of research software engineering GPU applications” at the SE4Science workshop at the International Conference on Computational Science in June 2020.

Alessio has attended the GPU Hackathon at Sheffield University as a mentor to gather experience with running hackathons and workshops. We plan to organize workshops like these ourselves in the future, where the idea is to invite project partners and others to submit proposals for codes that could use or improve their use of GPUs. During such a workshop a team of experienced engineers will help the participants with porting and optimizing their GPU codes.

Ben is currently developing material for an instructor-led tutorial on Kernel Tuner, and several members of the GPU SIG, including Hanno, are involved in testing and co-developing the material.

Ben and Alessio are currently preparing the GPU Programming course for eScience engineers on November 9, 2020. In addition, they will be teaching GPU programming courses in the ASCI research school course in that is currently in preparation for last week of November/early December, as well as the European PRACE course on GPU portability that will be in organized the 2nd or 3rd week of December. There is also an ongoing effort to add a GPU programming lesson to the “Software Carpentry” style courses offered by the center.

## Plans for the period until the end of April 2021
<!--  help text goes here  -->
In this section, list what plans you have for this SIG. Describe each plan according to the following format:

- **every three weeks** regular SIG meetings where eScience engineers, students, and external speakers present a topic
- **November 9, eScience center internal GPU Programming course**: Ben and Alessio will be giving an internal and online GPU programming course to the eScience engineers. Several other members of the GPU Computing SIG will help out with answering questions during the hands-on programming exercises.
- **Late November/Early December, ASCI A24 GPU Programming course**: Ben and Alessio will be teaching a full day course on GPU programming to computer science PhD students as part of a week-long course of the ASCI research school.
- **2nd/3rd week of December, PRACE GPU Programming course**: Currently in preparation, Ben and Alessio and possibly other members of the GPU Computing SIG will be involved in teaching how to port scientific codes to GPUs.


## What are the expected outputs of the SIG?

- More and updated GPU Computing expertise among eScience engineers currently working on eScience projects that require GPU expertise.
- Knowledge sharing between eScience engineers working on different projects.
- A platform for asking feedback and questions to colleagues regarding compute-intensive problems.
- Constructively working together and sharing knowledge with the HPC and ML groups at SURFSara.
- Establishing and maintaining the position of the Netherlands eScience center as a national and international center of excellence in GPU Computing, through teaching courses, creating new and maintaining existing collaborations.
- Keeping our expertise in heterogeneous computing up to date, in a landscape that is rapidly diversifying, with plenty vendor-driven software innovations and emerging computing platforms. Our projects demand both expertise in low-level software engineering as well as down-stream, high-level packages such as tensor flow for ML or domain-specific languages.
