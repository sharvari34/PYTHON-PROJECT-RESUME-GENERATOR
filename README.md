# PYTHON-PROJECT-RESUME-GENERATOR
📄 Resume Generator using Streamlit
A web application that helps you quickly generate a professional resume from a simple form. This tool was built to simplify the resume creation process, allowing you to focus on the content without worrying about the formatting.

🚀 **Overview**

This application provides a web-based form where users can enter their full name, contact information, work experience, skills, and other relevant details. Upon submission, the backend script uses the python-docx library to construct a Microsoft Word document and offers it as an immediate download.

⚙️**How It Works**
  1. The user interface is rendered using Streamlit.
  
  2. User fills out the resume form.
  
  3. On clicking "Generate Resume", the input data is passed to a Python function.
  
  4. The function uses python-docx to build a .docx file in memory.
  
  A download button is presented to the user to save the generated file.

💻 **How to Run This Project Locally**

  1. Clone the repository:

           git clone https://github.com/your-username/your-repository-name.git

           cd your-repository-name
  
  3. Install the required libraries:
     
           pip install streamlit python-docx
  
  5. Run the Streamlit app:
     
           streamlit run your_script_name.py
Your browser should automatically open with the application running!
