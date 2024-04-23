# Gemini 2.0

Gemini 2.0 is a React.js-based chat application powered by an AI chatbot, designed to mimic the Gemini protocol.

## Features

- **Sidebar**: Allows users to initiate new chats and view recent prompts.
- **Main Interface**: Displays chat interface, greeting messages, suggested prompts, and chat results.
- **Gemini API Integration**: Utilizes Google Generative AI API for generating responses.
- **Responsive Design**: Built with React.js for cross-device compatibility.

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Shivuu2803/gemini-2.0.git
cd gemini-2.0
```

2. Install dependencies using npm:

```bash
npm install
```

3. Obtain your Google Generative AI API key and update the `API_KEY` variable in `gemini.jsx`.

4. Run the project using npm:

```bash
npm run dev
```

Access the application in your browser at [http://localhost:3000](http://localhost:3000).

## Project Structure

- **src/components**: Contains React components for the sidebar, main interface, and other UI elements.
- **src/assets**: Stores image assets used in the application.
- **src/context**: Includes context providers for managing application state.
- **src/config**: Holds configuration files, including the Gemini API integration script.

## Usage

1. Open the application in your browser.
2. Use the sidebar to initiate a new chat or view recent prompts.
3. Enter a prompt in the input box and press "Send" to get a response from the chatbot.
4. Explore suggested prompts and interact with the chatbot to get responses.

## Contributing

Contributions to Gemini 2.0 are welcome! If you have any ideas for improvements or bug fixes, feel free to submit a pull request.
