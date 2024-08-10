# InfoBuddy with LLAMA 3.1 🦙

InfoBuddy is a lightning-fast chatbot built using LLAMA 3.1, Groq, and Streamlit in Python. Designed to be highly efficient and responsive, InfoBuddy assists clinicians and researchers by providing quick access to relevant information, checking new treatment options, and reviewing patient history, especially for rare conditions. This project aims to reduce information overload, minimize errors, and improve the overall quality of care in the healthcare industry.

![Screenshot (615)](https://github.com/user-attachments/assets/083b5a17-d99a-4c30-b16b-10e0862cbcf7)


## Features

- **Rapid Information Retrieval**: InfoBuddy can quickly access and deliver relevant research, treatment options, and patient history, helping clinicians make informed decisions.
- **Streamlined Workflow**: By integrating various sources of medical information, InfoBuddy reduces the time clinicians spend searching for data, allowing them to focus on patient care.
- **User-Friendly Interface**: Built with Streamlit, the interface is intuitive and easy to use, even for those with minimal technical expertise.
- **Groq-Optimized Performance**: Using Groq, the chatbot achieves exceptional speed and efficiency, making it ideal for high-demand environments.
- **LLAMA 3.1-Powered Intelligence**: InfoBuddy leverages the power of LLAMA 3.1 to understand complex queries and provide accurate, context-aware responses.

## Advantages

- **Time-Efficient**: Reduces the time clinicians spend on searching for information, leading to quicker decision-making and patient treatment.
- **Error Reduction**: By providing up-to-date and comprehensive data, InfoBuddy helps minimize errors that could arise from outdated or incomplete information.
- **Improved Patient Care**: By enhancing the efficiency and accuracy of information retrieval, InfoBuddy contributes to better patient outcomes.
- **Scalable and Flexible**: The architecture is designed to be scalable, allowing easy integration with additional data sources and medical databases as needed.
- **Open Source**: InfoBuddy is open-source, allowing the community to contribute, improve, and adapt the tool to different medical fields and use cases.

## Installation

To run InfoBuddy locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/infobuddy-llama3.1.git
   cd infobuddy-llama3.1
   
2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv env
   source env/bin/activate # On Windows use `env\Scripts\activate`

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt

4. **Run the Streamlit App**:
   ```bash
   streamlit run app.py
   
5. **Access the Chatbot**:
Open your browser and navigate to http://localhost:8501 to start interacting with InfoBuddy.

# Usage
Once the Streamlit app is running, simply enter your queries into the chat interface. InfoBuddy will process your request and provide detailed information based on the latest medical research, treatment guidelines, and patient history.
