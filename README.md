# Duplicate Detection with MSMP+ and Extended Clustering Methods

This repository contains the code for research aimed at improving duplicate detection methods for product datasets. By extending the traditional MSMP+ method with alternative hierarchical clustering techniques, the project evaluates the impact of complete and average linkage clustering on precision, recall, and overall performance.

**Author:** F.J. van Drunen 
**Contact:** 572793fd@eur.nl

This repository contains the code for an assignment completed as part of the **Computer Science in Business Analytics** course at **Erasmus University Rotterdam (EUR)**. The research focuses on improving duplicate detection methods for product datasets by extending the traditional MSMP+ method with alternative hierarchical clustering techniques. The project evaluates the impact of complete and average linkage clustering on precision, recall, and overall performance.


## Structure of Code

The code is structured in the following blocks of functions:

1. **[Functions] Extract Model Words and Create Binary Product Vectors**  
   Extracts meaningful model words from product titles and attributes, converting them into binary vectors for further processing.

2. **[Functions] Create Signature Matrix with Min-Hashing**  
   Reduces the dimensionality of binary vectors while preserving similarity by approximating Jaccard similarity.

3. **[Functions] Apply LSH to Find Nearest Neighbors**  
   Implements Locality Sensitive Hashing (LSH) to identify candidate duplicate pairs efficiently.

4. **[Functions] Apply MSM to Find Duplicate Products**  
   Utilises the Multi-component Similarity Method (MSM) to cluster candidate pairs based on similarity measures.

5. **[Functions] Evaluation Metrics**  
   Includes functions to calculate precision, recall, F1-score, and other metrics for evaluating duplicate detection performance.

## Usage

To replicate the research, the final cell in the provided script runs the bootstrapping process used in the study. This process applies the MSMP+ method with different hierarchical clustering strategies, optimises clustering thresholds, and evaluates results. Outputs are automatically exported to an Excel file
