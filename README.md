
# What Really Changes When Developers Intend to Improve Their Source Code: A Commit-Level Study of Static Metric Value and Static Analysis Warning Changes

## Introduction

This study delves into the impact of developer intentions on software quality enhancement, focusing on the challenges of measuring software quality. It emphasizes the subjective nature of software quality and the pivotal role of static software metrics and static code analysis as assessment tools. By analyzing commit messages through Natural Language Processing (NLP), this research infers developers' intentions, building upon the foundational work of Trautsch et al.

## Study Design

The approach begins with manual classification of commit messages from open-source Java projects. Recognizing the team's initial inexperience in commit classification, it leverages the classified data from Trautsch et al., albeit with modified dataset splits and distinct modeling techniques.

## Experiments

This research investigates two core questions:

1. The influence of developer intent on software metric values.
2. The types of files targeted for quality enhancements.

It employs various metrics to evaluate code changes categorized as perfective, corrective, or other, with a keen focus on the effects on size and quality. Both clustering and supervised models are utilized to analyze the data, testing hypotheses related to commit size and quality improvements.

## Findings

Key results affirm that perfective commits significantly differ from non-perfective ones and tend to positively influence metric values. Although supervised models outperformed clustering methods, they provided limited insights. This study introduces new variables (e.g., number of throw statements, nodes, method declarations, and invocations) and applies both clustering and supervised classifiers for a comprehensive analysis.

## Threats to Validity

Potential threats include clustering accuracy, noise within clustering, manual inspection of commit messages, sample selection, researchers' experience, limitations related to language and project type, and an open-source bias.

## Conclusion

The findings underscore the value of understanding developer intentions to elucidate the nature of changes aimed at improving software quality. This study corroborates several findings from the original study regarding the impact of intent on quality metrics.

## Keywords

- **Regression**: Predictive analysis, like estimating plant height based on water intake.
- **Classification**: Sorting entities into predefined categories, like balls into color-labeled boxes.
- **Clustering**: Grouping similar entities without prior categorization, akin to organizing a mixed pile of socks.
- **Decision Trees**: A flowchart-like structure used for making decisions based on data.
- **Neural Networks**: Complex networks mimicking the human brain to recognize data patterns.
- **Perfective Changes**: Code enhancements aimed at refining functionality without direct bug fixes, often leading to improved software quality metrics.
