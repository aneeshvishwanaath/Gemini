# AI ChatBot

A sophisticated chatbot built using the Gemini API. This chatbot is designed to handle a range of queries with intelligent responses, leveraging the capabilities of the Gemini API for enhanced interaction.

## Features

- **Intelligent Responses:** Provides accurate and relevant answers to various types of queries.
- **Gemini API Integration:** Utilizes the Gemini API for advanced conversational abilities and understanding.
- **Versatile Query Handling:** Capable of handling a broad spectrum of questions beyond specific domains.

## Getting Started

To get started with the AI ChatBot, follow these steps:

### Prerequisites

- Python 3.x
- Node.js and npm (for server-side operations)

### Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/aneeshvishwanaath/AI-ChatBot.git
    cd AI-ChatBot
    ```

2. **Set Up the Python Environment**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Python Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Install Node.js Dependencies**

    Navigate to the bot directory and install dependencies.

    ```bash
    cd bot
    npm install
    ```

5. **Configure Environment Variables**

    Create a `.env` file in the root directory and add necessary configuration details. Example:

    ```env
    GEMINI_API_KEY=your_gemini_api_key
    ```

6. **Run the Bot**

    Start the Python server and the Node.js server.

    ```bash
    # In one terminal
    python app.py
    
    # In another terminal
    cd bot
    npm start
    ```

## Usage

- **Default Prompt:** The chatbot starts with a default message about its capabilities. It is designed to provide responses to a wide range of queries.

- **Interacting with the Chatbot:** You can interact with the chatbot using the provided UI or test it via tools like Bot Framework Emulator.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Gemini API:** For providing advanced conversational capabilities and enhancing the chatbot's performance.

