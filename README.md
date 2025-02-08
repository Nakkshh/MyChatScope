# MyChatScope

MyChatScope is a Python-based application designed to process and analyze chat data. This guide will walk you through setting up and using the application.

## Live Demo

You can access MyChatScope here: [MyChatScope](https://mychatscope.streamlit.app)

## Features

- **Text Processing**: Cleans and prepares chat data for analysis.
- **Stop Words Removal**: Utilizes a custom list of Hinglish stop words to filter out common terms.
- **Data Analysis**: Provides insights into chat patterns and statistics.
- **Individual and Group Analysis**: View chat analysis for the entire group or specific individuals.
- **Word Cloud Generation**: Visual representation of the most used words in the chat.
- **Most Used Words**: Identifies the frequently used words in conversations.

## How to Use

1. **Export Chat from WhatsApp**:
   - Open WhatsApp and navigate to the chat you want to analyze.
   - Click on the three dots (menu) and select `More > Export chat`.
   - Choose `Without media` and save the `.txt` file.

2. **Upload the Text File**:
   - Open MyChatScope on your browser: [MyChatScope](https://mychatscope.streamlit.app/)
   - Browse and upload the exported `.txt` file.

3. **Analyze the Chat**:
   - Click on `Show Analysis` to view insights about your chat data.
   - You can analyze chats for the entire group or specific individuals.

## Prerequisites

Ensure you have the following installed:

- [Python 3.x](https://www.python.org/downloads/)

## Installation

1. **Clone the Repository**:

   Open your terminal and run:

   ```bash
   git clone https://github.com/Nakkshh/MyChatScope.git
   cd MyChatScope
   ```

2. **Set Up a Virtual Environment** (Optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```

3. **Install Dependencies**:

   Install the required Python packages using the provided `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Prepare Your Chat Data**:

   Ensure your chat data is in a compatible format for processing.

2. **Run the Application**:

   Execute the main application script:

   ```bash
   python App.py
   ```

   The application will process the chat data and provide analytical insights.

## Features & Functions

- **Stop Words**:
   - The application uses a custom list of Hinglish stop words located in the `stop_hinglish.txt` file.
   - You can modify this file to add or remove stop words as needed.

- **Word Cloud**:
   - Generates a visual representation of the most frequently used words in the chat.

- **Most Used Words**:
   - Lists the most frequently used words and their counts.

- **Message Count**:
   - Displays the number of messages sent by each participant.

- **Daily Activity Timeline**:
   - Shows the chat activity trend over time.

- **Hourly Activity**:
   - Analyzes chat activity based on time of day.

- **Top Emojis Used**:
   - Identifies the most frequently used emojis in the chat.

- **User-Specific Analysis**:
   - View chat analysis for each individual, including their most used words and activity patterns.

## Contributing

Contributions are welcome! If you'd like to improve this project, please fork the repository and create a pull request.

## License

This project is open-source. Feel free to use and modify it as per your needs.



