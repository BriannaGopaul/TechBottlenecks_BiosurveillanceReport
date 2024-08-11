# Technological Bottlenecks for PCR, LAMP, and Metagenomic Sequencing

**Authors:** Ziyue Zeng, Brianna Gopaul  
**Supervisor:** Akhil Bansal

## Executive Summary

A robust biosurveillance system would aim to identify and monitor new and known pathogens with the goal of reducing the severity of pandemics. From past pandemics, it’s clear that modern biosurveillance systems have the potential to improve tremendously. To do so, a better understanding of the bottlenecks biosurveillance systems face is needed.

The report consists of two standalone parts. This is part II of the report that assumes a broad understanding of the biosurveillance and pathogen detection. We focus primarily on three technologies that are commonly used for biosurveillance: Polymerase Chain Reaction (PCR), Loop-Mediated Isothermal Amplification (LAMP), and Metagenomics Sequencing. If you would like to access an introduction to the biosurveillance landscape and an overview of the different technologies used, please see part I of the report [here](https://github.com/BriannaGopaul/Tech_Bottlenecks_Biosurveillance_Report/blob/main/Overview%20of%20the%20Pathogen%20Biosurveillance%20Landscape%20%20(3).pdf).

In this report, we explore the importance of technological bottlenecks and investigate a few bottlenecks to gain a deeper understanding of their core issues. We focused on identifying the primary technological bottlenecks in metagenomics sequencing, LAMP, and PCR. Towards the end, we also did an exploratory analysis on the non-technological bottlenecks that biosurveillance systems face.

This report will be most useful if you would like to have a deeper understanding of PCR, LAMP, and metagenomics sequencing and how they can be applied in biosurveillance. We also highlighted some potential avenues for technological improvements that could be worthwhile for research and funding agencies to look into.

We used a combination of empirical research and expert interviews to gather information throughout the project. A list of the organizations that we have talked to is included in the Appendix. In total, we gathered the opinions of 25 experts and sourced over fifty peer-reviewed research papers.

## Chapter I - Technological Bottlenecks for PCR, LAMP and Metagenomic Sequencing

The key bottlenecks and some potential solutions for PCR, LAMP, and metagenomics are listed in the table below.

### PCR & LAMP

| **Technologies** | **Description** | **Key bottlenecks** | **Potential solutions** |
|------------------|-----------------|---------------------|-------------------------|
| **PCR**          | Nucleic-acid based diagnostic. Gold standard for pathogen amplification and detection due to its high sensitivity and accuracy | Long sample-to-answer time: RNA extraction takes 50 minutes, amplification takes 70 minutes. Costs tens of thousands of USD | Eliminate RNA purification step by direct-to-test addition |
| **LAMP**         | A non-PCR, nucleic-acid based alternative that’s gaining attention. Performs at a comparable level of sensitivity as PCR, while having inherently lower cost and a quicker time to detection | High temperature needed for optimal performance. High risk of carry-over contamination | Use phosphorothioated primers that allow for optimal performance at lower temperature. Improve CRISPR/Cas9 based methods or other methods to reduce crossover contamination |

### Metagenomic Sequencing

Metagenomic sequencing enables researchers to sample the genes within a biological sample. It is currently used for oncology and whole genome sequencing but has potential to be used in biosurveillance. The ideal metagenomic sequencer diagnostic would be rapid, inexpensive, fully automated, and miniaturized for ubiquitous use. In this report, we break down metagenomic sequencing into sample preparation, library preparation, and sequencing.

| **Process** | **Technological Bottlenecks** |
|-------------|-------------------------------|
| **Sample Preparation** | Samples suffer from low concentration rates of the pathogen material and high contamination rates. Need better sample concentration and filtration methods to remove contaminants |
| **Library Preparation** | Current methods require lab personnel to use external equipment to prepare samples. Requires automation and integration of library preparation methods with sequencers. High in costs due to aforementioned reasons. |
| **Sequencing** | Need miniaturization of sequencers as current sequencers are large benchtop devices used in lab settings. Depending on the read length, sequencers can take hours to days. A focus on decreasing the read out time of sequencers is needed for rapid detection. The costs of these devices are too high today. |

In doing this research, we have also noticed that metagenomic sequencing suffers from misalignment of incentives. Today, funding is driving innovation in metagenomic sequencing for oncology and whole genome sequencing use. As the technology is developed for these applications, they become less suitable for its use as a diagnostic tool.

## Chapter II - Discussion on Non-Technological Bottlenecks

While we initially hypothesized that technological bottlenecks were crucial to biosurveillance systems, we gradually realized throughout research that non-technological bottlenecks are equally important and even more neglected. There are many stages involved in order to implement an effective and robust biosurveillance system - from funding, regulatory approval, R&D, manufacturing, implementation, distribution, adoption to ensuring that data is interoperable between different systems. We ranked the relative importance of each of these bottlenecks for PCR, LAMP, and metagenomic sequencing, but have relatively low confidence on the exact rankings as we explored it in shallow depth.

We suspect that although much work can be done to improve biosurveillance technologies, we also urgently need more people working on addressing the less tangible non-technological bottlenecks. We believe that it would be useful to explore deeper into these non-technological bottlenecks and their potential solutions.

See the full report in the repo for more details.
