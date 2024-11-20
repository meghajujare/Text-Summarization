# Text Summarization Streamlit App ✍️📝

This is a **Text Summarization** web application built using **Streamlit** 🚀 and powered by **Cohere API** 💬 to provide high-quality text summaries. The app allows users to input text and receive a concise summary based on their chosen length.

## Features 🌟
- **Text Summarization**: Enter any text, and the app will generate a summarized version 📜.
- **Summary Length Control**: Choose the length of the summary in sentences (from 1 to 5) 📊.
- **Easy-to-Use Interface**: Simple interface where you input the text, adjust the length slider, and generate the summary 🖱️.

## How to Use 🛠️

1. **Enter Text**: Type or paste the text you want to summarize into the text box ✍️.
2. **Select Summary Length**: Use the slider on the sidebar to choose how many sentences the summary should contain 🎚️.
3. **Generate Summary**: Click the **Generate Summary** button to get your summary ⚡.

## Demo 🎥
You can access the live app here:  
[Text Summarization Streamlit App](https://text-summarization-wjsufrrgtcs9wdn7e4yunp.streamlit.app/) 🌐

## Technologies Used 🛠️
- **Streamlit**: For building and deploying the web application 💻.
- **Cohere API**: For generating text summaries based on the provided input 🧠.
- **Python**: Backend programming language 🐍.

## Installation Instructions 📥

### Prerequisites:
- Python 3.x 🔧
- Streamlit 🌟
- Requests 📦
- Cohere API key (you need to sign up at [Cohere](https://cohere.ai/) for an API key 🔑).

### Steps to run the app locally 🖥️:

1. **Clone the repository** (if you're working with a repo):
   ```bash
   git clone <repository_url> 🚀
   ```

2. **Navigate to the directory**:
   ```bash
   cd <your_app_directory> 📂
   ```

3. **Install the required dependencies**:
   ```bash
   pip install streamlit requests ⚙️
   ```

4. **Set up Cohere API Key**:
   Replace the placeholder `cohere_api_key` in the script with your actual API key:
   ```python
   cohere_api_key = "YOUR_COHERE_API_KEY" 🔑
   ```

5. **Run the Streamlit app**:
   ```bash
   streamlit run text_summarization_app.py ▶️
   ```

6. Open your browser and go to `http://localhost:8501` to use the app 🌐.

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details 📃.

## Acknowledgments 🙏
- **Cohere API** for providing powerful language models for text summarization 💡.
- **Streamlit** for making it easy to create interactive web apps 🌍.

