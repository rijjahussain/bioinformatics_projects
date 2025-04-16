# 🧬 NGS Analysis Pipeline (Colab-based)

This is a simple, end-to-end NGS analysis pipeline implemented in **Google Colab** using publicly available E. coli data from the SRA.

## 🚀 Steps Performed:
- Downloading raw FASTQ from SRA
- Quality check (FastQC)
- Adapter trimming (Trim Galore + Cutadapt)
- Alignment to reference (BWA)
- Variant calling and filtering (SAMtools + bcftools)
- Visualization (matplotlib, seaborn)

## 📊 Output:
- Quality reports
- Filtered VCF with SNPs & INDELs
- Variant distribution plots (by position, type, and quality)

## 📎 Sample Plot
![variant_plot](outputs/variant_plot.png)

## 💻 Try it yourself
[Open in Google Colab](https://colab.research.google.com/github/yourusername/ngs-pipeline-colab/blob/main/NGS_Pipeline.ipynb)

## ⚙️ Requirements
- Google Colab
- Python 3.11+
- Tools: BWA, SAMtools, FastQC, Trim Galore, Cutadapt

## 🔗 References
- SRA Accession: SRR2584863
- Reference genome: *E. coli* (NCBI)

---
*Made with ❤️ for bioinformatics learning*
