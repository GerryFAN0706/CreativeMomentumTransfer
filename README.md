# Creative Momentum Transfer: How Timing and Labeling of AI Suggestions Shape Iterative Human Ideation

## IJCAI HAI Special Track Publication

These materials are provided in support of the paper titled "Creative Momentum Transfer: How Timing and Labeling of AI Suggestions Shape Iterative Human Ideation," accepted at the IJCAI Human-Aware AI (HAI) Special Track.

## Abstract

Human–AI collaboration is increasingly integral to a variety of domains where creative ideation unfolds in iterative cycles, yet most existing studies evaluate AI-generated concepts in a single step. This paper addresses the gap by investigating "Creative Momentum Transfer"—how the timing (early vs. late) and labeling (AI-labeled vs. unlabeled) of AI prompts shape multi-round human ideation. In a between-subjects experiment (N = 247), participants proposed solutions for plastic pollution over two rounds, with AI suggestions introduced either at the outset or mid-process and labeled explicitly or not. Results reveal that early AI prompts increase overall creativity but induce stronger anchoring, whereas late AI prompts trigger a mid-round pivot that fosters more divergent thinking yet still boosts final outcomes compared to a no-AI control. Labeling amplifies both subjective and objective adoption of AI ideas, although most participants could detect AI sources even when unlabeled. Furthermore, qualitative interviews highlight nuanced perspectives on perceived ownership, authenticity, and the ways in which labeling triggers deeper scrutiny of the AI's style. By demonstrating that baseline creativity moderates these effects more robustly than trust in AI, this study advances our theoretical understanding of multi-round human–AI synergy while offering design guidelines for next-generation creativity support systems. We discuss how user-centered design can balance rapid convergence (via early AI) with strategic pivot opportunities (via late AI) and weigh transparent labeling against ethical considerations of authorship and user autonomy.

## Materials Provided

This repository contains the data and analysis code associated with the aforementioned paper.

### Data

The data is provided in CSV format:

*   `prestudy_data.csv`: Contains data collected during the pre-study phase, including demographic information, baseline creativity scores, and Trust in AI scale responses.
*   `round1_data.csv`: Contains data from the first round of the creative ideation task. This includes participant responses, timing data, and condition assignments.
*   `round2_data.csv`: Contains data from the second round of the creative ideation task, including refined or new solutions, and timing data.
*   `post_task_data.csv`: Contains data from the post-task evaluation, including perceived influence of external suggestions, creative self-efficacy scores, and source recognition responses for unlabeled groups.

Each file contains 249 lines, corresponding to the N=247 participants after exclusions, plus a header row.

### Code

*   `Creative_Momentum_analysis_code.ipynb`: A Jupyter Notebook containing the Python code used for data analysis presented in the paper. This includes:
    *   Data loading and preprocessing.
    *   Statistical analyses (ANOVAs, t-tests, moderation analyses, repeated-measures ANOVA).
    *   Generation of figures and tables reported in the paper.

## Instructions

1.  **Data**: The CSV files can be opened with any standard spreadsheet software (e.g., Microsoft Excel, Google Sheets, LibreOffice Calc) or loaded into statistical software (e.g., R, Python with pandas).
2.  **Code**:
    *   To run the `Creative_Momentum_analysis_code.ipynb` notebook, you will need a Python environment with Jupyter Notebook or JupyterLab installed.
    *   Required Python libraries include (but may not be limited to): pandas, numpy, scipy, statsmodels, matplotlib, seaborn. You can typically install these using pip (e.g., `pip install pandas numpy scipy statsmodels matplotlib seaborn`).
    *   Ensure the CSV data files are in the same directory as the notebook, or update the file paths within the notebook accordingly.
    *   Open the notebook and run the cells sequentially to reproduce the analysis.

## Citation

If you use these materials, please cite the original paper:

Fan, G., Liu, D., Pan, L., & Huang, Y. (2025). Creative Momentum Transfer: How Timing and Labeling of AI Suggestions Shape Iterative Human Ideation. *Proceedings of the International Joint Conference on Artificial Intelligence (IJCAI)*. (Note: Update with full citation details once available).
