# DSPy RAG Implementation

This repository contains an implementation of a Retrieval-Augmented Generation (RAG) system using DSPy, a framework for optimizing language model prompts and weights.

## Overview

This project demonstrates how to:
- Set up a DSPy environment
- Implement a RAG system
- Optimize the system using DSPy's BootstrapFewShot
- Evaluate the system's performance

The implementation uses the HotPotQA dataset for multi-hop question answering.

## Requirements

- Python 3.7+
- DSPy
- OpenAI API key (for GPT-3.5-turbo)

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/nileshchopda/dspy-rag-implementation.git
   cd dspy-rag-implementation
   ```

2. Install the required packages:
   ```
   pip install dspy-ai openai
   ```

3. Set up your OpenAI API key as an environment variable:
   ```
   export OPENAI_API_KEY='your-api-key-here'
   ```

## Usage

Run the following notebook to train and evaluate the RAG system:

```
DSPy_RAG.ipynb
```

This will:
1. Set up the DSPy environment
2. Load and prepare the HotPotQA dataset
3. Define and compile the RAG system
4. Test the system with a sample question
5. Evaluate the system's performance on the development set

## Files

- `DSPy_RAG.ipynb`: Main script containing the RAG implementation
- `requirements.txt`: List of required Python packages

## Results

The system achieves DSPy RAG pipeline on the HotPotQA development set.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- DSPy developers and community
- HotPotQA dataset creators
