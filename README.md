
## Smart Summarizer SaaS App 


### Introduction
This Software as a Service (SaaS) application using Streamlit. The application integrates with MongoDB for authentication, provides text summarization and translation features using OpenAI's GPT-3.5 model, and offers subscription-only access to certain tools. This project aims to provide powerful text summarization and translation tools, leveraging the capabilities of advanced AI models. 
Application is designed with security and user experience in mind. utilizing robust authentication mechanisms and ensure a seamless interaction with AI-powered services. By focusing on both ease of use and advanced capabilities, we aim to cater to a wide range of users, from casual to professional.


### Directory Structure
```
streamlit-saas/
│
├── .env                   # Environment variables for the app (e.g., database credentials, API keys)
├── .gitignore             # List of files and directories to be ignored by Git
├── Home.py                # Main home page for the application
├── mongo_auth/            # Directory containing MongoDB authentication logic
├── Pages/                 # Directory containing additional pages for the app (not detailed in the provided structure)
├── README.md              # This README file
├── requirements.txt       # Python dependencies required for the app
├── utils.py               # Utility functions for the app (e.g., email verification, user registration)
└── __pycache__/           # Directory for Python cache files
```

### Setting Up

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ryanshrott/saas.git
   cd SmartSummarizer
   ```

2. **Install Dependencies**:
   Use the following command to install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Environment Variables**:
   Update the `.env` file with the necessary credentials and API keys.

4. **Run the Streamlit App**:
   ```bash
   streamlit run Home.py
   ```

### Features

- **User Authentication**: The application integrates with MongoDB to authenticate users. New users can register, while existing users can log in.

- **Text Summarization Tool**: After logging in, users can use a text summarization tool, which leverages OpenAI's GPT-3.5 model to provide summaries of the provided text.

- **Subscription-only Translation Tool**: Subscribed users gain access to an exclusive translation tool. This tool translates text into the user-specified language using the GPT-3.5 model.

- **Email Verification**: New users need to verify their email address after registering. If they don't, they'll receive a reminder to do so.

- **Subscription Management**: Users can check their subscription status and access subscription-only tools. Non-subscribed users will be redirected to a payment URL.

### Conclusion

This SaaS application aims to provide seamless and efficient text summarization and translation services, leveraging the power of AI to enhance user productivity and accessibility.
---
