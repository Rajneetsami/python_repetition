# Python Revision for Data Engineering

This repository is created to revise and practice Python fundamentals and data engineering concepts.

I was a student in the **Data Engineer Batch 2023** at **Stockholm Tekniska Högskolan**.

To keep my skills updated and reinforce my learning, I organized my notes, exercises, and projects in this repository.

## 🛠️ Tools & Technologies

The following tools and technologies are used in this repository:

- **Python**  
  Core programming language for data engineering practice.

  python --version
  
  pip --version

- **Visual Studio Code (VS Code)**  
  Code editor used for development and project management.

- **Git & GitHub**  
  Version control and repository hosting.
  
  git --version

- **uv (Virtual Environment & Package Manager)**  
  Used to create and manage isolated Python environments and dependencies.

## ⚙️ Environment Setup (Using uv)

install uv tools:

pip3 install uv

Create virtual environment:

uv venv

Activate environment:

source .venv/bin/activate  # Mac/Linux
.venv\Scripts\activate     # Windows

create requirement.txt file

uv pip freeze > requirements.txt

Install dependencies:

uv pip install -r requirements.txt


- **Jupyter Notebook**  
  Used for experimentation, data exploration, and analysis.

  uv pip install ipykernel


## Folder Structure
 - 00_intro
 - 01_git_and_github
 - Excercise
