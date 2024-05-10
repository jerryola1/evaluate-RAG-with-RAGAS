# Evaluation of Q&A Responses

This repository contains Python code for evaluating the quality of answers provided to specific questions based on given contexts and ground truth answers. The evaluation is done using custom metrics from the `ragas` package.

## Requirements

To run this code, you need to install the following Python libraries:
- `datasets`: for managing structured datasets.
- `pandas`: for data manipulation and analysis.
- `ragas`: custom library for evaluating Q&A pairs.

You can install these packages using pip:
```bash
pip install datasets pandas
pip install ragas  
```
# Overview of the Script
The script performs the following steps:

- Defines a sample dataset containing questions, answers, relevant contexts, and the ground truth answers.
- Converts this data into a Dataset object from the datasets library.
- Evaluates the answers using two metrics from the ragas library: faithfulness and answer_correctness.
- Saves the evaluation scores to a CSV file.

# Usage
To execute the script, simply run the Python file in your environment:
```bash
python app.py
```

# Output
The result of the script is a CSV file named score.csv that contains the evaluation scores for the provided answers against the ground truth.

For further details or if you encounter any issues, please refer to the official documentation of the used libraries or raise an issue in this repository.

This README is structured to provide clear and concise instructions on how to install, run, and understand the output of the script. If there are specific features or behaviors of the script that are not covered, you may want to add additional sections as needed.
