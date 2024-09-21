# Virtual Interview Chatbot README

## Overview

The Virtual Interview Chatbot is an innovative tool designed to streamline the interview preparation process for job candidates and automate candidate assessments for HR professionals. By leveraging cutting-edge AI technologies, including Crewai and Gemini, this chatbot evaluates candidates through simulated interviews, providing insights into their strengths and weaknesses along with a final decision. This tool not only helps candidates prepare effectively but also allows HR teams to save time and focus on more strategic tasks.

### Why Use This Tool?

- **Enhanced Preparation**: Candidates can practice common interview questions and receive real-time feedback, enabling them to improve their responses.
- **Automated Assessments**: HR professionals can automate the initial evaluation process, reducing the time spent on screening candidates.
- **Actionable Insights**: The chatbot generates detailed reports highlighting pros, cons, and overall recommendations, helping HR teams make informed decisions.
- **User-Friendly Interface**: Designed with ease of use in mind, candidates can interact with the chatbot effortlessly, simulating a real interview environment.

## Features

- Simulated interview experience with customizable questions
- Assessment report detailing candidate strengths and areas for improvement
- Integration with Gemini API for advanced analysis
- Easy setup and user-friendly interface

## Getting Started

### Prerequisites

To run this application locally, ensure you have the following installed:

- Python 3.x
- Pip

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ayushchamp/Interviewgpt.git
   cd Interviewgpt
   ```

2. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your environment variable**:
   - You need to add your Gemini API key to your environment variables:
     ```bash
     export GOOGLE_API_KEY='your_gemini_api_key'
     ```

### Running the Application

1. **Start the chatbot**:
   ```bash
   streamlit run main.py
   ```

2. **Interact with the chatbot**:
   - Open your web browser and navigate to `http://localhost:8501` to begin the interview process.

### Contribution

We welcome contributions! If you have suggestions for improvements or new features, please feel free to submit a pull request or open an issue on GitHub.