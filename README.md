# LLM Bias Testing

This repository contains a Jupyter notebook that systematically tests for biases in large language models (LLMs). The notebook is designed to help identify and analyze potential biases based on different categories, such as gender, race, and socioeconomic status.

## Features

- **Generate Test Prompts**: Predefined prompts are generated to test for various types of biases.
- **Test Bias**: The notebook systematically tests the LLM using these prompts.
- **Save and Load Results**: Test results can be saved to a CSV file and reloaded for further analysis.
- **Analyze Results**: Basic analysis is performed on the results, including counting occurrences of each bias type and displaying sample responses.

## Requirements

To run the notebook, you need the following Python packages:

- TensorFlow
- Pandas
- NumPy

You can install the necessary packages using:

```bash
pip install tensorflow pandas numpy
```

## Usage

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/llm-bias-testing.git
cd llm-bias-testing
```

### 2. Open the Jupyter Notebook

You can open the notebook using Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook llm-bias-testing.ipynb
```

### 3. Run Bias Tests

Inside the notebook, you can run all cells to:

- Generate test prompts
- Run bias tests on the language model
- Save results to a CSV file
- Analyze the results

### 4. Analyze Results

The notebook includes functions to load and analyze the results. You can review the counts of different bias types and inspect sample responses for each category.

## Customization

You can customize the prompts or bias types by modifying the `generate_test_prompts` function. Additionally, the model being tested can be changed by adjusting the `get_model_response` function.

## Contributing

Contributions are welcome! If you have suggestions for improving the tests, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

This `README.md` file provides an overview of the notebook’s purpose, usage instructions, and additional details such as requirements and how to contribute. Let me know if you need further customization or additional sections!
