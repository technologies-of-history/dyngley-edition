---
title: "About"
menu: "main"
weight: 50
---

## Crowd-sourcing Dyngley's Digital Library

Old Books, New Science is designed as a student-centered digital humanities initiative, intended to introduce undergraduate students at Texas Christian University in the course [Technologies of History from Cuneiform to Coding](https://technologies-of-history.github.io/course) to both digital and historical research methods. Students undertake the work of transcribing Dyngley's manuscripts as one of several "digital tools" assignments taught during the course, which traces the history of communications technologies from the invention of writing in the ancient Near East, to the invention of coding. Each week, students are introduced to digital projects, archives, or initiatives that facilitate more open and accessible research into these communications technologies. As students visit these projects, they learn about the digital infrastructure that makes much of this work possible and to gain experience working with particular "digital tools."

Students work with Dyngley's manuscripts as the central component of their third digital tools assignment. For this assignment, students are assigned a set of pages to transcribe in plain text files (one for each page of the manuscript), which are then uploaded into a GitHub repository, [technologies-of-history/dyngley-data](https://github.com/technologies-of-history/dyngley-data). 

After completing their transcriptions and uploading their .txt files to a branch of the dyngley-data repository, students generate pull requests to alert the lead editor, Dr. Melissa Reynolds, that files should be checked over for errors. Once each transcription file has been checked, Dr. Reynolds merges these pull requests into the dyngley-data repository, pulls these uploaded files down into her local repository, and runs the EditionCrafter CLI to generate the necessary XML and IIIF files for the edition. For more on this specific assignment, view the [assignment description](https://technologies-of-history.github.io/course/digitaltools3) on the course syllabus, or check out students' reflections on the work of transcription on our course [blog](https://technologies-of-history.github.io/spring-2026).

For more on the workflow and command line interface for EditionCrafter, view the User Guide at [EditionCrafter.org](https://editioncrafter.org).

## Site Infrastructure

This site was developed on a Hugo template hosted on [GitHub pages](https://github.com/technologies-of-history/dyngley-edition). The linked repository contains the basic content for the site: the Introduction, About, and Credit pages. The data and metadata generated from the manuscript transcriptions and annotations are held in a separate GitHub repository, [technologies-of-history/dyngley-data](https://github.com/technologies-of-history/dyngley-data). The two repositories are linked to one another with [EditionCrafter](https://editioncrafter.org), a publication tool for digital critical editions developed by the [Making and Knowing Project](https://makingandknowing.org/) (M&K) and [Performant Software Solutions](https://www.performantsoftware.com/), with funding from the National Science Foundation. 

## Developing EditionCrafter

EditionCrafter is an open-source, customizable publishing tool that will allow users to deploy their own texts, data, and commentary as low-maintenance digital critical editions. It enables the creation of static sites that rely on basic well-established technologies and workflows to address issues of longevity, maintenance, sustainability, and cost. For more about this work, see the NSF award announcement: [Crafting an Open Source Digital Publication Tool for the History of Science](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2218218&HistoricalAwards=false).

This project builds upon the publication of *[Secrets of Craft and Nature. A Digital Critical Edition of BnF Ms. Fr. 640](https://edition640.makingandknowing.org/#/)* by the Making and Knowing Project. 

## Contact

Dr. Melissa Reynolds
[m.reynolds1[at]tcu.edu](mailto:m.reynolds1@tcu.edu)