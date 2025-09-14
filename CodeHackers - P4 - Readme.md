# CodeHackers - P4 - Code

This project presents a scalable and interpretable framework to evaluate AI agents, focusing on multiple performance dimensions:


Coherence & Accuracy – How logical and factually correct responses are.
Instruction Following – How well the agent adheres to the prompt.
Hallucination Detection – Detecting false or unsupported information.
Assumption Control – Avoiding unwarranted assumptions.


We trained and compared two AI agents, DeepSeek and Nemotron, on a curated dataset, producing measurable results for each metric. This demonstrates the framework’s ability to systematically benchmark AI agents.


Features - 
Batch preprocessing for handling large datasets efficiently.
Automated scoring across multiple dimensions.
Generation of interpretable reports and comparisons.
Modular design that can be scaled to hundreds of agents.


Technologies Used -
Python – Core programming language
Hugging Face – Model training and inference
Pandas & NumPy – Data handling and processing
Matplotlib – Visualizations of results and trends


Results
The framework outputs scores for each agent across all metrics and provides clear visualizations. While demonstrated on a small dataset, it is designed to scale for large-scale AI evaluation.
Future Work
Extend to more AI agents and diverse domains (QA, summarization, reasoning).
Incorporate explainable AI techniques to interpret low scores.
Build interactive dashboards for real-time evaluation monitoring.
