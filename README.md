# Flask Voting Application with Git Workflow

## Project Description
This project is a simple web application built using Python and Flask.  
It demonstrates how different URLs (endpoints) return different responses, similar to how real websites like amazon.com/orders or amazon.com/cart work.  
The app also showcases Git branching workflow, where all development happens in the `dev` branch and only stable code is merged into `main`.  
 
Basic endpoints (`/`, `/health`) 
- Version 1 : Voting system with `/vote/<name>`, `/results`.
- Version 2: Enhancement Voting system with `/reset`.

## Installation and Setup
Follow these steps to run the project locally:

```bash
# Clone the repository
git clone git@github.com:Sahana2509/Flask_Apllication_with_Github.git
cd Flask_Apllication_with_Github

# Create virtual environment
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install flask

# Run the application
python app.py

