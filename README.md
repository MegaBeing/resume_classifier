# Resume Classifier and Recommendation

## Introduction

This is an NLP project focused on the classification of resumes into various profiles. Additionally, it provides recommendations to improve your resume, helping you to get shortlisted in a highly competitive job market.

## Features

- **Google Gemini API Integration**: Utilizes the Google Gemini API for personalized resume improvement recommendations, fine-tuned to address specific concerns about your resume.
- **Robust Deep Learning Libraries**: Employs advanced deep learning libraries to ensure efficient and effective outputs.
- **High Accuracy**: Achieves an accuracy of 92% on the training dataset and 65% on the test dataset.

## Requirements

To run this project, you will need:

- Python
- tensorflow
- numpy 
- matplotlib
- pandas 
- gemini api key
Some libraries are mentioned in the notebook itself

## Installation

Follow these steps to install and set up the project:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/resume-classifier-recommendation.git
    cd resume-classifier-recommendation
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install tensorflow numpy pandas matplotlib google-api-python-client
    ```

4. Set up Google Gemini API:
    - Follow the instructions to set up the Google Gemini API and obtain the necessary credentials.
    - Place the credentials file in the project directory.

## Usage

Once the installation is complete, you can use the project as follows:

1. Prepare your resumes and place them in the `resumes` directory.
2. Run the resume classification and recommendation script:
    ```bash
    python classify_recommend.py
    ```
3. The classified resumes and recommendations will be displayed and saved in the `output` directory.

## Conclusion

The Resume Classifier and Recommendation project is a powerful tool for anyone looking to improve their resumes and increase their chances of getting shortlisted. Leveraging advanced NLP techniques and the Google Gemini API, this project provides valuable insights and recommendations to enhance your
