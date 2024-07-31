
# Code Explainer Gen AI Project

This project leverages the PaLM 2 API to create a code explainer tool that assists in understanding and documenting Python code. The tool takes in Python code and generates explanations, making it easier to comprehend and utilize.

## Features

- **Code Explanation**: Generate detailed explanations for given Python code snippets.
- **Documentation**: Create documentation for code bases with minimal effort.
- **User-friendly Interface**: Easy-to-use interface for interacting with the code explainer.

## Installation

To get started with the project, clone the repository and install the required dependencies.

```sh
git clone <your-repository-url>
cd <your-repository-directory>
pip install -r requirements.txt
```

## Usage

1. **Set up API Keys**:
   - Obtain your PaLM 2 API key from the provider.
   - Set the API key in your environment variables or in a configuration file.

2. **Run the Code Explainer**:

   ```sh
   python main.py
   ```

   Replace `main.py` with the entry point of your project if it's different.

3. **Input the Code**:
   - Provide the Python code snippet you want to explain.
   - The tool will generate and display the explanation.

## Configuration

Ensure you have your PaLM 2 API key set up correctly. You can do this by setting an environment variable:

```sh
export PALM2_API_KEY='your-api-key'
```

## Example

Here’s a quick example of how to use the tool:

```python
from code_explainer import CodeExplainer

code_snippet = """
def add(a, b):
    return a + b
"""

explainer = CodeExplainer(api_key='your-api-key')
explanation = explainer.explain(code_snippet)
print(explanation)
```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the existing style and conventions.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## Contact

If you have any questions or need further assistance, please contact Vijeta Raj at rajvijeta24@gmail.com.
