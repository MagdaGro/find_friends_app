Find Friends App 🧩

An interactive web application that helps users discover groups of people with similar interests and preferences using Machine Learning clustering.

The app collects a few user preferences, assigns the user to a group using a pre-trained clustering model, and presents insights about that group through interactive visualizations.

✨ Features

User preferences form – enter information such as age, education, favorite animals, preferred places and gender.

Machine Learning-based clustering – assign users to a group using a pre-trained clustering pipeline.

Group insights – display information about the assigned group, including its size and characteristics.

Interactive visualizations – explore group distributions through charts.

Data processing – load and process data from CSV and JSON files.

🛠️ Technologies

Python – application logic

Streamlit – interactive web application interface

Pandas – data loading and manipulation

PyCaret – loading and applying the pre-trained clustering model

Plotly Express – interactive data visualizations

CSV / JSON – data storage and input formats

⚙️ How It Works

The user enters their preferences in the application.

The app processes the submitted information.

A pre-trained Machine Learning clustering pipeline predicts the user's group.

The application displays the assigned group and the number of people belonging to it.

Interactive charts provide an overview of the group's characteristics, such as age, education, favorite animals, preferred places and gender.

🚀 Getting Started

Prerequisites

Python 3.x

pip

Installation

Clone the repository:

git clone <YOUR_REPOSITORY_URL>
cd <YOUR_PROJECT_DIRECTORY>

Install the required dependencies:

pip install streamlit pandas pycaret plotly

Make sure the required data files and pre-trained model are available in the expected project directories.

Run the application:

streamlit run app.py

Open the local URL displayed in your terminal to use the application.

📊 Example Use Case

A user enters their preferences, including age, education level, favorite animals and preferred places.

The application uses the pre-trained clustering pipeline to identify a group with similar characteristics. The user can then explore the group's profile through interactive charts and statistics.

🎓 Project Background

This project was developed as part of my learning journey in Python, Data Science and Artificial Intelligence.

It provided practical experience in building an interactive Python application, working with structured data, integrating a pre-trained Machine Learning model and presenting results through data visualizations.

👩‍💻 Author

Created as a personal educational project while developing practical skills in Python and Data Science.
