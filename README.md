# BioLLM Explorer

##Link to app web version: www.bio-llm.com

##Link to app download (Windows OS only at the moment)

https://drive.google.com/file/d/1ZLHBJOJ0N0ZgFwjz--BTi7i6C5QT1f3i/view?usp=sharing

##Link to Video Instruction

https://psu.zoom.us/rec/share/-6UCX4kD9ivBMMPefhB1JjdwmXYVJtowgFO3lLF_WPrbLt8XsETaWRs2KH2RnZ8W.6Dl__YBAgFNFGrgJ?startTime=1741285836000

## Overview

BioLLM Explorer is an advanced AI-powered analysis tool for biomedical research. This application leverages large language models to analyze genetic data, SNP associations, and drug-disease relationships, helping researchers discover and interpret complex biomedical connections more efficiently.

## Features

- 🧬 **Three Primary Analysis Modes**:
  - Gene Analysis
  - SNP Analysis
  - Drug Repurposing

- 📊 **Comprehensive Data Collection**:
  - PubMed literature search
  - NCBI Gene database retrieval
  - dbSNP variant lookup
  - Clinical trials data search

- 🤖 **AI-Powered Analysis**:
  - Interprets collected information
  - Identifies biological pathways
  - Assesses association strengths
  - Evaluates functional impacts

- 📁 **Flexible Output**:
  - Detailed text files for each entity-disease pair
  - Optional summary CSV files
  - Confidence assessments and evidence ratings

## Prerequisites

- OpenAI API Key (obtain from [OpenAI Platform](https://platform.openai.com/api-keys))

## Installation

1. Extract the BioLLM Explorer folder to your preferred location
2. Run the executable file `BioLLM_Explorer.exe`
3. Enter your OpenAI API key when prompted
4. Wait for initial dependency installations

## Usage

### Input File Format

Create a simple text file (.txt) with tab or comma-separated columns:

- **Gene Analysis**: `gene_symbol,disease_name`
- **SNP Analysis**: `snp_id,disease_name`
- **Drug Analysis**: `drug_name,disease_name`

#### Example SNP Analysis Input
```
rs429358,Alzheimer's disease
rs7412,Alzheimer's disease
rs1801133,Cardiovascular disease
```

### Running an Analysis

1. Select the analysis type from the main menu
2. Browse and select your input file
3. Choose an output directory
4. Click "Run Analysis"
5. Monitor progress in the log window

### Generating Summaries

1. Select "Generate Summary from Results"
2. Choose the directory with analysis results
3. Click "Generate Summary"
4. A CSV file will be created in the "association_summary" subdirectory

## Technical Details

### Data Sources

- **Gene Analysis**: NCBI Gene, PubMed, gene expression databases
- **SNP Analysis**: dbSNP, GWAS catalog
- **Drug Repurposing**: Clinical trials, molecular pathway databases

### Output

- Detailed text files per entity-disease pair
- Comprehensive CSV summaries
- Confidence assessments
- Functional interpretations

## Troubleshooting

- **Missing API Key**: Check settings
- **Input File Format**: Ensure comma or tab delimited
- **Missing Scripts**: Reinstall application
- **Analysis Failure**: Check log window

## Support

For questions, bug reports, or feature requests, contact: sfz5259@psu.edu

## Legal & Privacy

- OpenAI API key stored locally in encrypted configuration
- No data sent to external servers
- All API calls made directly to OpenAI
- Analysis results remain on local machine

## Disclaimer

Users are responsible for OpenAI API usage costs.

---

**Thank you for choosing BioLLM Explorer!**
