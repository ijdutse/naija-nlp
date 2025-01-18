# Contributing to NLP for low-resource languages Research Tracker

Thank you for your interest in contributing to the **NLP for low-resource languages Research Tracker**! This repository aims to curate and organise research papers, resources (datasets, tools), and tutorials in NLP for low resource languages with emphasis on Nigerian languages. 
Your contributions are highly appreciated and will help make this resource more valuable for the community.

## How to Contribute

### 1. **Fork the Repository**
   - Click the `Fork` button at the top right of the repository page to create your own copy of the repository.

### 2. **Clone the Repository**
   - Clone your forked repository to your local machine:
     ```bash
     git clone https://github.com/ijdutse/naija-nlp.git
     cd naija-nlp
     ```

### 3. **Create a New Branch**
   - Create a new branch for your contribution:
     ```bash
     git checkout -b your-branch-name
     ```
   - Use a descriptive branch name, such as `add-sentiment-analysis-paper` or `update-datasets-list`.

### 4. **Make Your Changes**
   - Add or modify files in the appropriate folders (e.g., `papers/`, `datasets/`, `tools/`).
   - Follow the formatting guidelines below to ensure consistency.

### 5. **Commit Your Changes**
   - Stage your changes:
     ```bash
     git add .
     ```
   - Commit your changes with a clear and concise message:
     ```bash
     git commit -m "Add: New paper on sentiment analysis"
     ```

### 6. **Push Your Changes**
   - Push your changes to your forked repository:
     ```bash
     git push origin your-branch-name
     ```

### 7. **Create a Pull Request (PR)**
   - Go to the original repository on GitHub and click the `Compare & pull request` button.
   - Provide a clear title and description for your PR, explaining what changes you made and why.
   - Submit the PR, and the maintainers will review it.

---

## Formatting Guidelines

To maintain consistency across the repository, please follow these guidelines when contributing:

### 1. **Research Papers**
   - Add papers to the appropriate markdown file in the `papers/` folder.
   - Use the following format (see sample entry):
     ```markdown
     ### [Paper Title](link-to-paper)
     - **Authors**: Author 1, Author 2, etc.
     - **Summary**: A brief summary of the paper (1-2 sentences).
     - **Key Insight**: Highlight the main contribution or finding.
     ```

   Example:
   ```markdown
   ### [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
   - **Authors**: Jacob Devlin et al.
   - **Summary**: Introduces BERT, a transformer-based model that achieves state-of-the-art results in NLP tasks.
   - **Key Insight**: Pre-training on large corpora and fine-tuning on specific tasks improves performance.
   ```

 ### 2. **Datasets**
   - Add datasets to the appropriate markdown file in the 'datasets/' folder. See example:
   - Example: 
  
   ```
   ### [Dataset Name](link-to-dataset)
   - **Description**: A brief description of the dataset.
   - **Language(s)**: The languages covered by the dataset.
   - **Size**: The size of the dataset (if available).
   - **License**: The license under which the dataset is distributed.
 
  ```

