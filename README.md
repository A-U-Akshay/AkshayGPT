# AkshayGPT: Conversational AI Chatbot

AkshayGPT is a conversational AI chatbot designed to interact with users and provide quick, contextual answers to their queries. Built with the **LangChain** and **Streamlit** frameworks, it integrates the powerful **Llama model** (version 3.2) from LangChain’s community package for efficient natural language processing.

## Features
- **Real-time Interaction**: Users can input queries and receive responses instantly via the Streamlit interface.
- **Efficient Model**: Powered by the Llama model, AkshayGPT processes queries quickly and provides accurate, contextually relevant responses.
- **Modular Design**: Easily customizable prompt and response management for tailoring behavior and processing flow to specific use cases.
- **Adaptable Setup**: Can be adjusted to suit specific applications, making it versatile for various conversational AI scenarios.
- **Structured Backend**: LangChain handles prompt generation, model selection, and output parsing, ensuring a smooth and efficient process.

## Tech Stack
- **LangChain**: Manages the backend structure, including prompt creation, model selection, and output handling.
- **Streamlit**: Provides an interactive, user-friendly frontend for real-time querying and response viewing.
- **Llama Model 3.2**: Used for processing and generating natural language responses.

## How It Works
1. **Frontend (Streamlit)**: Users input their queries through a simple, intuitive interface.
2. **Backend (LangChain + Llama Model)**: LangChain’s backend structure handles the processing of queries and selects the appropriate model to generate a response.
3. **Real-time Feedback**: Streamlit updates the interface with the generated response, providing users with quick answers.

## Customization
The modular structure of AkshayGPT makes it easy to adjust and extend. You can modify the prompt generation, response parsing, and model configuration to adapt the chatbot for different domains or use cases.

## Getting Started

### Prerequisites
- Python 3.x
- Streamlit
- LangChain
- Llama Model (version 3.2 or compatible)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/A-U-Akshay/AkshayGPT.git
    cd AkshayGPT
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

4. Open the URL provided by Streamlit in your browser to start interacting with AkshayGPT.

## Usage

Once the app is running, you can type your queries in the input box, and the chatbot will respond with accurate and contextually relevant answers. The backend efficiently handles each query and updates the response in real time.

## Contributing

Feel free to fork the repository, make changes, and submit pull requests. Contributions are welcome to enhance the functionality and capabilities of AkshayGPT.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- **LangChain**: For providing the backend framework and language models.
- **Streamlit**: For offering an easy-to-use frontend for creating interactive apps.
