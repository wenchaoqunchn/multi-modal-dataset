# Dataset Introduction

In the context of software development, which is an ongoing evolutionary process, the ability to elicit evolutionary requirements is paramount for maintaining software competitiveness and enhancing user satisfaction. Traditional methods of collecting user feedback—such as surveys and social media interactions—often fall short due to inherent biases and the subjective nature of user expressions. In contrast, user interaction behavior data offers a more objective and detailed insight into how users engage with software systems.

Our dataset is designed to support our approach in leveraging user behavior data to extract evolutionary requirements. By integrating multi-modal user behavior data, we aim to quantitatively evaluate user experience and utilize behavior pattern mining to effectively elicit requirements.

## Directory Structure

The dataset is organized into 20 directories, labeled `P01` through `P20`, with each folder containing a singular JSON file named `Behavior_Sequence.json`. This structure allows for straightforward access to the behavior data of individual participants, facilitating comparative analysis while ensuring clarity in data organization.

## Behavior Sequence JSON File Structure

Each `Behavior_Sequence.json` file encapsulates an array of objects that detail user interactions with the software. Each object contains several key fields:

- **operationId**: A unique identifier for the operation.
- **page**: The page where the operation occurred.
- **module**: The module associated with the operation.
- **widget**: The specific widget involved in the interaction.
- **startTimeTick**: The timestamp (in ticks) when the operation started.
- **duration**: The duration of the operation in milliseconds.

This structured format captures the entire task execution process, providing essential insights into user engagement and interaction dynamics. The detailed nature of this data enables researchers to analyze user behaviors comprehensively and establish connections to specific evolutionary requirements.

## Research Context

Our study involved 20 graduate students in computer science, who engaged with a course management system. The experiment aimed to evaluate our proposed framework for eliciting evolutionary requirements using user interaction data.

### Research Questions

1. **RQ1**: How effective is our approach in eliciting evolutionary requirements based on user behavior data?
2. **RQ2**: How useful are the inferred evolutionary requirements in practical applications?

## Experiment Design

Participants performed various tasks, including logging in, creating courses, and registering new accounts. This design aimed to capture a wide range of interactions, enriching our dataset with diverse user behavior patterns.

## Usage

We invite researchers to utilize this dataset for further exploration into user behavior and requirements elicitation. For detailed insights into our methodology and findings, please refer to our original paper.

