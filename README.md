# Goog Goog
Simple Bot for short event

# Installation
1. `git clone`
1. `pip install rasa rasa-x`
1. `pip install rasa-x --extra-index-url https://pypi.rasa.com/simple`

# Run Rasa X
1. `rasa x`

# Deployment
1. `docker-compose up`

# Talk to Bot
1. `POST http://localhost:5005/webhooks/rest/webhook` with `json` payload
    ```bash
    {
      "sender": "Rasa",
      "message": "Hi there!"
    }
    ```
