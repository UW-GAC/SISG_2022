This site contains course materials for SISG Module 17: Computational Pipeline for WGS Data, July 27-29, 2022. **Course evaluations and certificates of completion will be available via the [official SISG course web page](https://si.biostat.washington.edu/courses/SM2217)** (requires login). 

- **Instructors:** Ken Rice, Laura Raffield, and Matthew Conomos
- **TAs:** Deepti Jain and Anya Mikhaylova
- **Zoom Link:** https://washington.zoom.us/j/91863603677
- **Slack Discussion:** https://app.slack.com/client/T015W8GL1CM/C03KLGG4XRV

## Course Format

#### Lectures
Course material will be presented through lectures given via Zoom. Slides for lectures are linked in the schedule below, and recordings of the lectures will be posted afterwards.

#### Exercises 
Many of the lectures will be followed with hands-on exercises. Students will be split into Zoom breakout rooms where they can work through the exercises together. Afterwards, the instructors will walk through the exercises and lead a discussion. 

To run the exercises, log into [NHLBI BioData Catalyst powered by Seven Bridges](https://platform.sb.biodatacatalyst.nhlbi.nih.gov) with your username and password -- we will use this platform for all live demonstrations during the course.

All of the R code and data can also be downloaded from the [github repository](https://github.com/UW-GAC/SISG_2022) from which the site is built and run on your local machine. Download the complete workshop data and exercises: https://github.com/UW-GAC/SISG_2022/archive/master.zip


## Schedule

NOTE: All times are Pacific Daylight Time (GMT-07:00)

**Wednesday, July 27th**

| Time | Topic | Lecture | Exercises/Discussion |
| --- | --- | --- | --- |
| 11:30am-11:40am | Introduction | [Slides](), [Recording]() | |
| 11:40am-12:30pm | Using BioData Catalyst powered by Seven Bridges | [Slides](), [Recording]() | |
| 12:30pm-1:30pm | Intro to Genomic Data Structure | [Slides](), [Recording]() | [Markdown](), [R code](), [Recording]() |
| 1:30pm-1:45pm | _Break_ | | | 
| 1:45pm-2:30pm | Association Tests Part I: Background | [Slides](), [Recording]() | |

**Thursday, July 28th**

| Time | Topic | Lecture | Exercises/Discussion |
| --- | --- | --- | --- |
| 8:00am-8:50am | Association Tests Part II: Single Variant Tests | [Slides](), [Recording]() | |
| 8:50am-9:45am | GENESIS for Single Variant Association Tests | [Slides](), [Recording]() | [Markdown](), [R code](), [Recording]() |
| 9:45am-10:15am | _Break_ | | | 
| 10:15am-11:45am | Population Structure and Relatedness Inference | [Slides](), [Recording]() | [Markdown](), [R code](), [Recording]() |
| 11:45am-12:45pm | _Lunch_ | | | 
| 12:45pm-2:00pm | Mixed Model Association Testing | [Slides](), [Recording]() | [Markdown](), [R code](), [Recording]() |
| 2:00pm-2:30pm | R shiny Apps for Exploring Results | [Slides](), [Recording]() | |

**Friday, July 29th**

| Time | Topic | Lecture | Exercises/Discussion |
| --- | --- | --- | --- |
| 8:00am-9:00am | Association Tests Part III: Multiple Variant Tests | [Slides](), [Recording]() | |
| 9:00am-10:00am | Variant Annotation for Aggregate Association Testing | [Slides](), [Recording]() | [Markdown](), [R code](), [Recording]() |
| 10:00am-10:30am | _Break_ | | | 
| 10:30am-11:15am | Annotation Explorer Demo | [Slides](), [Recording]() |  |
| 11:15am-12:00pm | Advanced Annotation Strategies for Association Testing | [Slides](), [Recording]() |  |
| 12:00pm-1:00pm | _Lunch_ | | |
| 1:00pm-2:00pm | Recent Findings from Sequencing Studies | [Slides](), [Recording]() |  |
| 2:00pm-2:30pm | Open Q&A | | [Recording]() |


## R packages used

- [GENESIS](http://bioconductor.org/packages/release/bioc/html/GENESIS.html)
- [SeqArray](http://bioconductor.org/packages/release/bioc/html/SeqArray.html)
- [SeqVarTools](http://bioconductor.org/packages/release/bioc/html/SeqVarTools.html)
- [SNPRelate](http://bioconductor.org/packages/release/bioc/html/SNPRelate.html)
- [TopmedPipeline](https://github.com/UW-GAC/analysis_pipeline/tree/master/TopmedPipeline)
- [tidyverse](https://www.tidyverse.org)
- [GGally](https://cran.r-project.org/web/packages/GGally)


## Resources

NHLBI BioData Catalyst Powered by Seven Bridges 

- [Getting Started Guide for SISG21 Module 16](https://drive.google.com/file/d/1LMlzot2GXPKCRmLH6BtsOi9PxKAoohYT/view?usp=sharing)

If you are new to R, you might find the following material helpful:

- [Introduction to R](http://faculty.washington.edu/kenrice/rintro/indexSEA15.shtml) materials from SISG Module 3
- Graphics with [ggplot2](https://ggplot2.tidyverse.org/)
- Data manipulation with [dplyr](http://dplyr.tidyverse.org/)
