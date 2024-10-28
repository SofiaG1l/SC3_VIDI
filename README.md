-   [A Tipping Point – VIDI Project](#a-tipping-point-vidi-project)
    -   [1. Algorithm to visually explore the factors associated with
        climate change
        adaptation](#algorithm-to-visually-explore-the-factors-associated-with-climate-change-adaptation)
    -   [2. Database of articles about individuals’ and societies’
        factors associated with climate change
        adaptation](#database-of-articles-about-individuals-and-societies-factors-associated-with-climate-change-adaptation)
    -   [3. Two applications of the algorithm and the
        database](#two-applications-of-the-algorithm-and-the-database)
        -   [(a) Patterns in Reported Adaptation Constraints: Insights
            from Peer-Reviewed Literature on Floods and Sea-Level
            Rise](#a-patterns-in-reported-adaptation-constraints-insights-from-peer-reviewed-literature-on-floods-and-sea-level-rise)
        -   [(b) Incremental and Transformational Climate Change
            Adaptation Factors in Agriculture Worldwide: A Natural
            Language Processing Comparative
            Analysis](#b-incremental-and-transformational-climate-change-adaptation-factors-in-agriculture-worldwide-a-natural-language-processing-comparative-analysis)

In this repository, you will find a summary of all the projects where I
was involved as a post-doc at [TU Delft](https://www.tudelft.nl/en/tpm),
Netherlands.

# A Tipping Point – VIDI Project

**Abstract** Climate change is one of the most pressing topics of the
21st century. As the time to mitigate its possible impacts has passed,
now it is important that individuals and societies start to adapt. This
makes the study of individuals’ and societies’ drivers and constraints
to climate change adaptation of paramount importance, but so far there
is a lack of standardized information to analyze such topics worldwide.
To fill this gap, we designed a pipeline to derive databases using
peer-reviewed articles’ text. We use Machine Learning and Natural
Language Processing to extract the articles’ findings. Then, we derived
a database that, later, we used to perform descriptive and statistical
analyses of climate change adaptation to floods and sea-level rise, as
well as, to study farmers’ incremental and transformational adaption
worldwide. We argue that the use of transparent methodologies to derive
data from text is increasingly necessary as, in general, the amount of
literature grows exponentially.

The main three outcomes for this project are:

1.  An algorithm to visually explore the factors associated with climate
    change adaptation.
2.  A database of articles about individuals’ and societies’ factors
    associated with climate change adaptation.
3.  Usage of the algorithm and the database to study two different
    climate change topics: (a) adaptation to floods and sea-level rise,
    and (b) farmers’ incremental and transformational adaptation to
    climate change.

In the following sections I further elaborate on them.

**Acknowledgments** This work was supported by the Netherlands
Organization for Scientific Research NWO VIDI grant number 191015. This
is the main project to which I was part of. For it, I worked together
with the [SC3](http://www.sc3.center/) members: [Prof. Tatiana
Filatova](http://www.sc3.center/team/tatiana-filatova/) (Principal
Investigator) and the PhD candidates [Thorid
Wagenblast](http://www.sc3.center/team/thorid-wagenblast/) and [Joos
Akkerman](http://www.sc3.center/team/joos-akkerman/).

## 1. Algorithm to visually explore the factors associated with climate change adaptation

**Abstract** The fast-growing number of research articles makes it
problematic for scholars to keep track of the new findings related to
their areas of expertise. Furthermore, linking knowledge across
disciplines in rapidly developing fields becomes challenging for complex
topics like climate change that demand interdisciplinary solutions. The
rise of machine learning-supported text analysis has been instrumental
in processing thousands of articles. Yet, how text relationships are
built remains a Black-Box for domain experts, making it difficult to
relate connected concepts to existing theories conceptualizing
cause-effect relationships and permitting hypothesis building and
testing. This paper presents an approach to sensibly use Natural
Language Processing by extracting variable relations and synthesizing
their findings using networks while relating to key concepts dominant in
relevant disciplines. As an example, we apply our methodology to analyze
farmers’ adaptation to climate change and compare the results with
mainstream text summarization methods. Furthermore, we validate our
methodology by asking experts to score and compare the outcomes. Results
show that using Natural Language Processing and networks descriptively
offer an interpretable way to synthesize literature review findings that
outperform mainstream text summarization methods. This methodology gives
not only the direction and the frequency of the association between the
words but also the frequency the word appears in the articles, which is
instrumental when performing literature reviews.

This work is currently under revisions in a journal. The working paper
can be accessed [here](https://arxiv.org/abs/2306.09737) and the codes
to reproduce and replicate the work are
[here](https://github.com/SofiaG1l/NLPnetworks4LR).

## 2. Database of articles about individuals’ and societies’ factors associated with climate change adaptation

The data for our two applications comes from Scopus (ELSEVIER, 2023).
The data was retrieved in two batches: during the last week of August
2022, and during the last week of January 2024. We derived the data from
articles that were about human adaptation to climate change and that
belonged to the categories: Multidisciplinary, Social Sciences, Arts and
Humanities, and Environmental Science. For both batches, we searched for
articles related to adaptation to climate change using search terms
related with climate change (e.g. “climat\[a-z\]\* change”,“…”).

The full explanation of our data derivation is here: \* Gil-Clavel,
Sofia; Filatova, Tatiana, 2024, “Interrelated Climate Change Adaptation
Measures and Factors”, <https://doi.org/10.17026/SS/PYZCXK>, DANS Data
Station Social Sciences and Humanities, DRAFT VERSION.

The codes to reproduce and replicate the work are
[here](https://github.com/SofiaG1l/Data_CCA).

## 3. Two applications of the algorithm and the database

### (a) Patterns in Reported Adaptation Constraints: Insights from Peer-Reviewed Literature on Floods and Sea-Level Rise

**Abstract** Understanding climate change adaptation constraints for
different actors – governments, communities, individuals, and households
– is essential, as adaptation turns into a matter of survival. Though
rich qualitative research reveals constraints for diverse cases, methods
to consolidate knowledge and elicit patterns in adaptation constraints
for various actors are scarce. Therefore, this work analyzes
associations between different adaptations and actors’ constraints to
climate-induced floods and sea-level rise. Our novel approach derives
textual data from peer-reviewed articles (published before February
2024) by using natural language processing, thematic coding books, and
network analysis. Results show that social capital, economic factors,
and government support are constraints shared among all actors.

This work is currently in the second round of revisions in a journal.
The working paper can be accessed
[here](https://osf.io/preprints/socarxiv/3cqvn). The codes to reproduce
and replicate the work will be published upon publication of the article
[here](https://github.com/SofiaG1l/FloodSLR_CCA). Also, the final
database that results from the analysis will be stored in DANS under:

-   Gil-Clavel, Sofia; Filatova, Tatiana, 2024, “Interrelated Climate
    Change Adaptation Measures and Factors”,
    <https://doi.org/10.17026/SS/PYZCXK>, DANS Data Station Social
    Sciences and Humanities, DRAFT VERSION;
    FloodsSLRDataFrame\_Phase1.csv \[fileName\].

### (b) Incremental and Transformational Climate Change Adaptation Factors in Agriculture Worldwide: A Natural Language Processing Comparative Analysis

**Abstract** Climate change is expected to adversely affect agriculture
worldwide. This is especially true if farmers fail to at least
incrementally adapt early in the twenty-first century, and fail to
pursue the transformational adaptation necessary to withstand future
climate changes. Many publications discuss the underlying mechanisms of
autonomous adaptation to climate change using quantitative, qualitative,
and mixed methods. However, the review of empirical evidence on
adaptation is usually performed on articles with quantitative data using
metanalysis, omitting much of the vast body of literature evidence based
on qualitative work. We address this gap by performing a comparative
analysis of factors associated with farmers’ climate change adaptation
in both quantitative and qualitative literature using Natural Language
Processing and generalized linear models. By retrieving publications
from Scopus, we derive a database with metadata and associations from
both quantitative and qualitative findings. We use the derived data as
input for generalized linear models to analyze whether farmers’ climate
change adaptation factors differ by type of adaptation (incremental
vs. transformational) and across different regions of the world. Results
show that factors related to informal institutions’ adaptive capacity
are more likely to be associated with transformational adaptation than
with incremental adaptation. Regarding world regions, results highlight
uneven access to income and infrastructure, with farmers in high-income
countries having an advantage, whereas farmers in low- and middle-income
countries require these the most for effective adaptation to climate
change.

This work is currently in the second round of revisions in a journal.
The working paper can be accessed
[here](https://osf.io/preprints/socarxiv/3dp5e). The codes to reproduce
and replicate the work will be published upon publication of the article
[here](https://github.com/SofiaG1l/Farmers_CCA). The final databases
that result from the analysis will be stored in DANS under:

1.  Gil-Clavel, Sofia; Filatova, Tatiana, 2024, “Interrelated Climate
    Change Adaptation Measures and Factors”,
    <https://doi.org/10.17026/SS/PYZCXK>, DANS Data Station Social
    Sciences and Humanities, DRAFT VERSION; FarmersDataFrame\_Phase1.csv
    \[fileName\].

2.  Gil-Clavel, Sofia; Filatova, Tatiana, 2024, “Interrelated Climate
    Change Adaptation Measures and Factors”,
    <https://doi.org/10.17026/SS/PYZCXK>, DANS Data Station Social
    Sciences and Humanities, DRAFT VERSION;
    FarmersDataFrame\_Phase2\_AllConnections.csv \[fileName\].
