# Financial_News_Research_Tool
It is a news research tool designed to extract valuable insights from stock market and financial articles. By leveraging advanced AI models like OpenAI embeddings and FAISS for similarity search, the tool allows users to input article URLs, process the content, and receive precise answers to specific queries based on the information in those articles.

How to Run:
Clone the Repository:
git clone url

Navigate to the Project Directory:
Install Dependencies:
pip install -r requirements.txt
Set Up OpenAI API Key:
Create a .env file in the project directory and add your OpenAI API key:
OPENAI_API_KEY=your_api_key_here
Run the Streamlit Application:
streamlit run main.py
The application will open in your browser. You can input URLs or upload a file containing URLs, process them, and ask queries based on the articles.
