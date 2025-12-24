# Traverz - AI-Powered Travel Platform

This is a travel platform that provides users with a variety of features to help them plan and book their trips. The platform is powered by AI and includes a chatbot, a recommendation engine, and a skills-based ranking system.

## Project Structure

```
├── SIH-2/
│   ├── static/
│   │   ├── css/
│   │   ├── images/
│   │   └── js/
│   ├── templates/
│   ├── app.py
│   └── requirements.txt
├── react-traverz/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   └── App.js
│   └── package.json
├── UI UX/
├── images/
├── initial/
└── README.md
```

## Getting Started

### Prerequisites

*   Python 3.8+
*   Node.js 14.x+
*   pip
*   npm

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/arib-06/SIH-2.git
    cd SIH-2
    ```

2.  **Set up the backend (Flask):**

    ```bash
    cd SIH-2
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3.  **Set up the frontend (React):**

    ```bash
    cd ../react-traverz
    npm install
    ```

### Running the Application

1.  **Start the backend:**

    ```bash
    cd SIH-2
    flask run
    ```

2.  **Start the frontend:**

    ```bash
    cd react-traverz
    npm start
    ```

## Tech Stack

*   **Backend:** Python, Flask
*   **Frontend:** React
*   **Database:** SQLite (default for Flask)
*   **APIs:** OpenAI, Google Maps

## Features

*   **Chatbot:** An AI-powered chatbot that can answer your travel-related questions.
*   **Recommendation Engine:** A recommendation engine that suggests destinations and activities based on your interests.
*   **Skills-Based Ranking System:** A gamified system that ranks travelers based on their skills and experience.
*   **Reels:** A feature that allows you to share your travel experiences with the community.
*   **Tourist Guide:** A directory of tourist guides that you can hire for your trips.
*   **Translation:** A tool that can translate text from one language to another.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.
