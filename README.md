# OntoPred: An efficient attention-based approach for Protein Function Prediction using skip-gram features

## Overview
Proteins play an essential role in performing many cellular functions in organisms and are responsible for various biochemical activities. The main objective of this task of protein function prediction is to annotate protein sequences with their correct functions, which are represented by Gene Ontology (GO) terms.  Recently, the number of new proteins released has been increasing. As the experimental approach of annotating these proteins is very time-consuming, the need for faster annotation techniques has arisen. Approaches using deep learning and machine learning have been shown to be beneficial in this regard. In this research, we propose a novel approach, OntoPred, for the task of function prediction which makes use of the standalone protein sequences and annotates them with their corresponding functions (GO terms). The core idea is to use an attention mechanism to identify which parts of a sequence influence the presence of a function. The model uses a combination of n-grams and skip-gram features extracted from the sequences. The proposed model was evaluated on multiple datasets including the CAFA3 evaluation benchmark. The maximal F1-scores obtained on the molecular function (MF), biological process (BP), and cellular component (CC) aspect on the CAFA3 evaluation benchmark are 0.566, 0.545, and  0.652 respectively. 

## Repository Link
Link to GitHub Repository:
https://github.com/suyash-chintawar/OntoPred

## File Structure
- Dataset.txt : Contains the links to the datasets used namely, UniProt-SP, CAFA3 Benchmark, GOLabeler dataset.
- Code/CAFA3 : Contains the python scripts used for the CAFA3 benchmark.
- Code/GOLabeler : Contains the python scripts used for the GOLabeler benchmark.
- Code/UniProt-SP : Contains the python scripts used for the proposed UniProt-SP dataset.
- Presentation.pdf : Additional resource for detailed explanation of the complete research.

## Publication details
Suyash Chintawar, Rakshit Kulkarni and Nagamma Patil, "OntoPred: An efficient attention-based approach for Protein Function Prediction using skip-gram features", Springer SN Computer Science Journal.(submitted - under review)



