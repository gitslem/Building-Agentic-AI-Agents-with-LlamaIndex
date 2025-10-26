
## 📖 About This Course

AI agents are quickly becoming popular for their ability to make decisions autonomously and then act upon them. In this hands-on interactive course for AI and ML engineers, instructor Kumaran Ponnambalam helps you get up to speed with agentic AI capabilities in LlamaIndex, the popular framework that provides several building blocks to quickly create and deploy AI agents with ease.

Along the way, explore a variety of different agentic AI use cases with LlamaIndex to understand popular patterns in agentic AI and how to implement them successfully with LlamaIndex.

---

## 💻 Repository Contents

This repository contains all the code, Jupyter notebooks, datasets, and supporting files you need to follow along with the course. Each notebook corresponds to a key concept or use case.

* `code_01_XX A basic Llamaindex agent.ipynb`
* `code_02_XX A Healthcare assistant agent with ReAct.ipynb`
* `code_03_XX Summarization with reflection.ipynb`
* `code_04_XX A simple workflow.ipynb`
* `code_05_XX ReAct agent with Workflows - Doctor scheduling.ipynb`
* `code_06_XX Multi-agent Hospital application.ipynb`
* `datasets/` - Contains all data files used in the notebooks.
* `lib/` - Contains utility functions for the course.
* `requirements.txt` - A list of all necessary Python packages.

---

## 🚀 Getting Started

To run these notebooks on your local machine, please follow these steps.

### 1. Clone the Repository
```bash
git clone [https://github.com/gitslem/Building-Agentic-AI-Agents-with-LlamaIndex.git](https://github.com/gitslem/Building-Agentic-AI-Agents-with-LlamaIndex.git)
cd Building-Agentic-AI-Agents-with-LlamaIndex
````

### 2\. Create a Virtual Environment (Recommended)

It's highly recommended to use a virtual environment to manage your dependencies.

```bash
# For macOS/Linux
python3 -m venv venv
source venv/bin/activate

# For Windows
python -m venv venv
.\venv\Scripts\activate
```

### 3\. Install Dependencies

Install all the required Python packages listed in `requirements.txt`.

```bash
pip install -r requirements.txt
```

### 4\. Set Up API Keys

This course requires API access to an LLM provider, such as OpenAI.

1.  Create a file named `.env` in the root of this project.

2.  Add your API key to this file:

    ```
    OPENAI_API_KEY="your-sk-api-key-here"
    ```

### 5\. Launch Jupyter Notebook

You are now ready to run the course notebooks.

```bash
jupyter notebook
```

This will open a new tab in your browser. Navigate to the `.ipynb` file you wish to run.

Clone. Learn. Build. 
CLB by Slem
Tutor: Kumaran Ponnambalam

<!-- end list -->

