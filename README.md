# Chatbot with NodeJS using the ChatGPT-3.5-Turbo API

This project is a chatbot built using Node.js and OpenAI's GPT-3.5 Turbo API. This chatbot works in the CLI of the computer and can easily be incorporated to make a standalone chatbot UI for website and apps.

## Table of Contents

- [Gallery](#gallery)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Built With](#built-with)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Gallery
<img src="./assets/Chatbot.png" alt="chatbot" width="600" />

https://github.com/AshleyCodes-1/Chatbot-with-NodeJS/blob/main/assets/Chatbot-demo.mp4

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Node.js installed on your machine. If not, you can download it from here.
- [NodeJS](https://nodejs.org/en)

### Installing

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required libraries by running the following command:

```bash
npm install dotenv colors openai readline-sync
```
## Built With

- [Node.js](https://nodejs.org/en): The runtime environment.
- [ChatGPT-3.5-Turbo-API](https://platform.openai.com/docs/models/gpt-3-5): OpenAI's ChatGPT API is used for generating and fetching responses.
- [dotenv](https://www.npmjs.com/package/dotenv): For managing environment variables.
- [colors](https://www.npmjs.com/package/colors): Adding colors to console text for a better output.
- [openai](https://www.npmjs.com/package/openai): The OpenAI API client for interacting with the ChatGPT-3.4 Turbo API.
- [readline-sync](https://www.npmjs.com/package/readline-sync): Synchronous Readline for the console.

## Configuration

1. Create a .env file in the project root and add your OpenAI API key:

```bash 
OPENAI_API_KEY=your_api_key_here
```

Replace "your_api_key_here" with your actual OpenAI API key.

2. Update the config.js file with any additional configuration settings.

## Usage
To start the chatbot, run the following command in your terminal in the project directory: 

```bash
npm start
```

## Contributing

We welcome contributions from the community! If you'd like to contribute to the chatbot, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:

    ```bash
    git checkout -b feature/your-feature-name
    ```

3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository detailing the changes you've made and why they should be merged.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
