# Gen-AI-Playground

This repository contains Jupyter notebooks from DeepLearning.AI courses focused on building systems with ChatGPT API and Red Teaming LLM applications. The notebooks provide hands-on examples and practical implementations of various AI concepts.

## Repository Structure
```
Gen-AI-Playground/ 
├── notebooks/ 
│ ├── Lab01/ # Building Systems with the ChatGPT 
│ └── Lab02/ # Red Teaming LLM Applications 
├── requirements.txt 
├── Dockerfile 
├── LICENSE
└── README.md
```

## Course Contents

### Lab 01 - Building Systems with the ChatGPT API 
- Language Models, Chat Format and Tokens
- Classification
- Moderation
- Chain of Thought Reasoning
- Chaining Prompts
- Check Outputs
- Evaluation
- Building a Custom Chatbot
Source: https://learn.deeplearning.ai/courses/chatgpt-building-system

### Lab 02 - Red Teaming LLM Applications
- Testing and finding vulnerabilities in LLM applications
- Prompt injection attacks
- Security evaluation
- Robustness testing
- LLM application safety
Source: https://learn.deeplearning.ai/courses/red-teaming-llm-applications

## Prerequisites

- Python 3.10 or higher
- Jupyter Notebook or JupyterLab
- OpenAI API key (required for Lab 01)

## Installation

### Option 1: Local Installation

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/Gen-AI-Playground.git
cd Gen-AI-Playground
```

2.  **Create and Activate Virtual Environment:**
```bash
    python -m venv venv
    # On macOS/Linux:
    source venv/bin/activate
    # On Windows (Command Prompt):
    venv\Scripts\activate.bat
    # On Windows (PowerShell):
    .\venv\Scripts\Activate.ps1
```
3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Install Jupyter Kernel for the Environment:**
    ```bash
    python -m ipykernel install --user --name=genai-playground
    ```
5. **Setup your Open API key:**
    ```bash
    # On Windows
    set OPENAI_API_KEY=your-api-key-here

    # On macOS/Linux
    export OPENAI_API_KEY=your-api-key-here
    ```
6.  **Open and Run Notebooks:** Navigate to the `notebooks/` directory and open each `.ipynb` file. Select the "genai-playground" kernel. Run the cells sequentially. If you encounter `ModuleNotFoundError` after installation, ensure your virtual environment is active and try restarting the Jupyter kernel and running the setup cell again.
    ```
7.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
8.  **Open and Run Notebooks:** Navigate to the `notebooks/` directory and open each `.ipynb` file. Select the "genai-playground" kernel. Run the cells sequentially. If you encounter `ModuleNotFoundError` after installation, ensure your virtual environment is active and try restarting the Jupyter kernel and running the setup cell again.


### Option 2: Using Docker 

Build the Docker image:
```bash 
docker build -t gen-ai-playground .
``` 
Run the container:
```bash 
docker run -p 8888:8888 -e OPENAI_API_KEY=your-api-key-here gen-ai-playground
``` 

### Option 3: Using VS Code
- Install the **"Python"** and **"Jupyter"** extensions in VS Code
- Open the repository folder in VS Code
- Select the **genai-playground** kernel when opening notebooks
- Install the recommended VS Code extensions (listed in **.vscode/extensions.json**)

### Troubleshooting
- OpenAI API Issues:
    - Verify your API key is correctly set
    - Check your API usage limits
    - Ensure you have proper internet connectivity

- Jupyter Kernel Issues:
    - Reinstall the kernel: python -m ipykernel install --user --name=genai-playground
    - Verify kernel selection in notebooks

- Package Conflicts:
- Try creating a fresh virtual environment
- Update pip: pip install --upgrade pip
- Install packages one by one to identify conflicts


### Contributing
- Fork the repository
- Create a feature branch
- Commit your changes
- Push to the branch
- Create a Pull Request

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgments 
- [www.deeplearning.ai](www.deeplearning.ai) for the original course content
- OpenAI for the ChatGPT API
- Giskard for the Red Teaming content

### Contact
For questions or issues, please open an issue in the repository. """




