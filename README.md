# Weco VSCE - Optimize Your Code Effortlessly  

A powerful Visual Studio Code extension for interacting with Weco AI’s code optimizer. Whether you’re looking to improve performance or refine code quality, Weco streamlines your workflow for a better development experience.

## Overview
Weco leverages advanced optimization techniques and AI language model strategies to iteratively improve your source code. It supports multiple model configurations, provides a live progress chart, and allows flexible setups to suit different optimization tasks.

## Installation & Requirements
- Visual Studio Code or a VSC fork like Cursor
- Python (if your evaluation script is in Python) 
- OpenAI API Key - the extension will prompt you to set one when first installed

## Quick Start
1. Open a folder or workspace in VS Code containing the code you want to optimize.  
2. Install the Weco extension and open its sidebar from the Activity Bar.  
3. Enter your OpenAI API key when prompted by the in-extension modal or through the Settings Modal (gear icon).  
4. Fill out the optimization fields:  
   - *(Optional)* **Analyze & Suggest**: Provide a simple “Task/Goal” for the built-in Auto-Config to propose default settings.  
   - **File to Optimize**  
   - **Evaluation Command** (e.g., `python evaluate.py`)  
   - **Metric Name** (e.g., “Accuracy” or “Time”)  
   - **Steps** (number of optimization iterations)  
5. **Run Optimization** - the extension will iteratively modify your code, run your evaluation script, and only keep improvements.

## Using the Optimization Sidebar
- **Task/Goal**: A short text describing your optimization target (e.g. “Speed up the sorting algorithm”).  
- **File to Optimize**: Click “Select File” or manually type the path.  
- **Evaluation Command**: The command that outputs a numeric metric; make sure it prints something like `MetricName: 0.92`.  
- **Steps**: Total number of iterations. More steps can yield better results but take longer.  
- **Advanced**: Provide custom instructions, like “use built-in libraries only.”

## Troubleshooting
- **No API Key**: The extension will keep prompting until a valid key is saved.  
- **Eval Script Issues**: If your command fails or no numeric metric is found, double-check your script output.  
- **No Improvement**: Provide more steps or refine your metric logic. The extension is only as good as the evaluation feedback.

## Feedback & Support
If you encounter bugs or have feature requests, please open an issue in this repository.

[![Follow @WecoAI on X](https://img.shields.io/badge/X-@WecoAI-1DA1F2?style=social&logo=twitter)](https://x.com/WecoAI)

---

Enjoy effortless code optimization with Weco VSCE!