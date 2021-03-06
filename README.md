This repository contains material and programme for the workshop "Using clouds and VMs in bioinformatics training". The slides and hands-on instructions can be found in the speaker-specific folders in the Materials section.

---
# [Using clouds and VMs in bioinformatics training](https://csc.fi/web/training/-/cloud-vm-bioinformatics)
#### [ELIXIR](https://www.elixir-europe.org/) [EXCELERATE](https://www.elixir-europe.org/excelerate) workshop 23.-25.5.2016, [CSC](https://www.csc.fi/how-to-reach-us), Espoo, Finland

This international workshop enables bioinformatics trainers and infrastructure specialists to share their experiences and knowledge on using clouds, virtual machine (VM) images and Docker, and it brings everybody abreast with the full potential of these technologies.

Bioinformatics analysis typically involves a large number of software and reference data, making the installation process a time-consuming task. This problem is aggravated in a course setting, where every participant needs to have an identical installation, sufficient hardware to run it, and, ideally, access to an identical set-up after the course. If participants use their own laptops, a lot of valuable course time is too often wasted on installation problems.

Ready-to-run virtual machine (VM) images and Docker containers containing pre-installed analysis software are gaining momentum in bioinformatics. They can be run on participant’s own computer, or better still on cloud platforms, which typically provide more computing power and memory, required for example for NGS analysis jobs. The additional benefit of using a VM/Docker and cloud is the easy scaling for running tens or hundreds of simultaneous jobs in a course setting. Bioinformatics and especially NGS analysis pose some additional challenges which will also be tackled: the VM images can get inconveniently large and they need to be updated often in order to keep reference data and analysis tools up to date.

This workshop introduces several cloud platforms from different countries, and it allows bioinformatics trainers to gain hands-on experience in running VM images and Docker containers in them. The dialogue between bioinformatics trainers and infrastructure providers also allows the latter to gain valuable knowledge on the special needs that bioinformatics training poses. 

#### Preliminary program

**Monday 23.5.2016**

9-12 Presentations, discussion and hands-on

- Welcome and backgroud *Eija Korpelainen (ELIXIR-FI)*, [materials](/materials/EijaKorpelainen)
- Introduction to compute clouds. *Vera Hansper (ELIXIR-FI)*, [materials](/materials/VeraHansper)
- Introduction to CSC's OpenStack [cPouta cloud](https://research.csc.fi/pouta-user-guide) and its Web UI Horizon. *Kalle Happonen / Jukka Nousiainen (ELIXIR-FI)*, [materials](/materials/elixir-fi)
- Creating consistent training environments in the cloud. Images? Automation? *Kalle Happonen / Jukka Nousiainen (ELIXIR-FI)*, [materials](/materials/elixir-fi)
- Introduction to CSC's [Pouta Blueprints software](https://github.com/CSC-IT-Center-for-Science/pouta-blueprints), a frontend to manage cloud resources and lightweight user accounts. *Seija Sirkiä and Olli Tourunen (ELIXIR-FI)*, [materials](/materials/PoutaBlueprints)
    - Hands-on using Pouta Blueprints to launch RStudio.
    - Overview of Pouta Blueprints
    
12-13 Lunch

13-17 Presentations, hands-on and discussion

- [cPouta cloud](https://research.csc.fi/pouta-user-guide): learn how to start a VM, add users and volumes, set up network and floating IP, and save a virtual machine image by taking a snaphot. *Kalle Happonen and Jukka Nousiainen (ELIXIR-FI)*, [materials](/materials/elixir-fi)

- Using clouds and VMs in bioinformatics training in Sweden. [Bioimg.org](https://bioimg.org/), a catalogue of virtual machine images for life sciences. *Ola Spjuth (UPPMAX, ELIXIR-SE)*, 30 min. 

- Workshop in a compute cloud: not that obvious *Markus van Dijk (SURFsara, ELIXIR-NL)*, [materials](/materials/Markus%20van%20Dijk)

**Tuesday 24.5.2016**

9-12 Presentations, hands-on and discussion

- Clouds & VM showcase from Australia: GVL as a platform for Bionformatics Training. *Andrew Lonie & Simon Gladman ([EMBL-ABR](https://www.embl-abr.org.au))*, 30 min

- [BTP](http://bib.oxfordjournals.org/content/early/2016/04/14/bib.bbw032.long): A cloud-based bioinformatics training platform. *Annette McGrath (CSIRO, Australia) & Jerico Revote (Monash eResearch Centre, Autralia)*, 30 min

- [Vagrant](https://www.vagrantup.com/) presentation and hands-on session. *Pedro Fernandes (ELIXIR-PT)*, 40 min, [materials](/materials/Pedro_Fernandes)

12-13 Lunch

13-17 Presentations, hands-on and discussion

- [INFN cloud](http://www.recas-bari.it/index.php/en/) activities for bioinformatics in Italy. Demo of the INFN cloud. *Stefano Nicotri (INFN, ELIXIR-IT)*, 45 min. [materials](/materials/stefano_nicotri)

- [French Bioinformatics Cloud](http://www.france-bioinformatique.fr/en/cloud). *Christophe Blanchet and Victoria Dominguez (ELIXIR-FR)*. 2.5 h. [materials](/materials/IFBcloud)

**Wednesday 25.5.2016**

9-12:30 Presentations, hands-ons and discussions

- [Clouds](https://www.egi.eu/solutions/fed-cloud/), VMs and other resources from EGI for bioinformatics training. *Diego Scardaci (EGI.eu/INFN) and Fotis Psomopoulos (Aristotle University of Thessaloniki)* [materials](/materials/Diego-Scardaci)

- Basic tools to exploit the [EGI FedCloud](https://www.egi.eu/solutions/fed-cloud/). 

- How to use bioinformatic applications running on the EGI FedCloud. *Fotis Psomopoulos (Aristotle University of Thessaloniki), Kimmo Mattila (ELIXIR-FI)*

12:30-13:30 Lunch

13:30-17 Presentations, hands-ons and discussions

- [Docker](https://www.docker.com/). *Abdulrahman Azab (ELIXIR-NO)*, 2 h. [materials](/materials/Docker)
 
- Using [Amazon Web Services (AWS)](https://aws.amazon.com/?nc2=h_lg) and Docker in training. *Nicolas Delhomme (Umeå Plant Science Center)*, 1.5 h. [materials](/materials/NicolasDelhomme)



