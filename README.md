Project Overview
The AI Resume Analyzer is a web-based application designed to help job seekers evaluate and improve their resumes. Users can upload their resume in PDF format, enter their target job role, and receive instant analysis with scores, keyword detection, and actionable suggestions. This project was built as part of an AI Agent development assignment and demonstrates practical application of automation, user input handling, and intelligent decision-making.

The application provides a complete end-to-end workflow starting from resume upload to generating detailed analysis reports. It uses a rule-based keyword matching algorithm to evaluate resumes across four categories: Technical Skills, Soft Skills, Experience, and Education. The system then calculates an overall score, generates category-specific scores, identifies missing keywords, and provides personalized improvement suggestions.

Key Features
Users can upload their resume in PDF format and enter their target job role along with their experience level. The application then performs instant analysis and provides an overall score out of 100, category-wise scores for Technical Skills, Soft Skills, Experience and Education, a role match percentage, detected keywords, missing keywords, and smart suggestions for improvement. Users can also download the complete analysis report as a text file and preview the extracted text from their resume. Quick role selection buttons are provided for common job roles like Software Engineer, Data Scientist, and DevOps Engineer.

Technology Stack
The application is built using Python 3.8 or higher as the backend programming language. Streamlit is used as the web application framework for building the user interface. PyPDF2 handles PDF text extraction. Custom CSS is used for modern and responsive UI design.

Installation and Setup
To install and run the application, first ensure you have Python 3.8 or higher installed on your system along with pip package manager. Download all project files to a folder on your computer. Open terminal or command prompt and navigate to the project folder. Install the required dependencies using the command pip install -r requirements.txt. Once the dependencies are installed, run the application using the command streamlit run app.py. Open your browser and navigate to http://localhost:8501 to access the application.

How It Works
The user workflow begins with uploading a resume in PDF format. The user then enters their target job role and selects their experience level from the dropdown menu. After clicking the Analyze Resume button, the system extracts text from the uploaded PDF using PyPDF2. The extracted text is then processed through a keyword matching algorithm that checks for over 100 predefined keywords across four categories. Based on the keyword presence, the system calculates an overall score and category-wise scores. The system also generates a role match score by checking job-specific keywords, identifies missing keywords that should be added, and provides personalized suggestions for improvement. Finally, the results are displayed in an organized dashboard with tabs for detailed analysis, suggestions, keywords found, and statistics. Users can download the complete report as a text file.

Scoring Categories
Technical Skills category carries 40 percent weight and checks for programming languages, web development frameworks, databases, cloud technologies, and data science tools. Soft Skills category carries 25 percent weight and checks for communication, leadership, problem solving, teamwork, and adaptability. Experience category carries 20 percent weight and checks for project management, development experience, and achievements. Education category carries 15 percent weight and checks for degrees and fields of study.

Tips for Better Score
To improve your resume score, use action verbs like Developed, Led, Created, and Implemented at the start of bullet points. Quantify your achievements using numbers such as Increased sales by 20 percent. Tailor your resume for each job application by customizing it according to the job description. Include industry-specific keywords from the job posting. Keep your resume concise, ideally one to two pages. Highlight achievements and focus on results rather than just listing responsibilities. Use a professional and clean format.

Project Structure
The project consists of four main files. The app.py file contains the main Streamlit application with all functionality. The requirements.txt file lists all Python packages required to run the application. The README.md file contains this project documentation. The architecture_diagram.png file shows the system architecture. The demo video link is provided above for demonstration.

Troubleshooting
If you encounter a ModuleNotFoundError, run pip install -r requirements.txt to install all dependencies. If you get a Port Already in Use error, run streamlit run app.py --server.port 8502 to use a different port. For PDF upload errors, ensure the file is a valid PDF format, the file size is less than 200 megabytes, and try converting the file to PDF if it is in another format.

Future Enhancements
Planned future enhancements include ATS compatibility score to check how well the resume performs against Applicant Tracking Systems, interview question generator based on the resume content, LinkedIn profile optimization suggestions, cover letter generator, multi-language support, salary recommendations, and job matching recommendations.
