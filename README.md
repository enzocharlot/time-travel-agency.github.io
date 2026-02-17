# TimeTravel Agency ⏳

Welcome to the **TimeTravel Agency**, a luxury service offering curated voyages to the most significant epochs in history. This project simulates a high-end booking platform for time travel, complete with an AI-powered concierge.

![TimeTravel Agency Hero](https://via.placeholder.com/800x400?text=TimeTravel+Agency+Hero)

## Features

-   **Immersive Design**: A premium, "temporal luxury" aesthetic using gold, obsidian, and glassmorphism effects.
-   **Epoch Destinations**: Detailed cards for Paris 1889, Florence 1504, Cretaceous Period, etc.
-   **AI Concierge "Chronos"**: A real-time chat widget powered by the **Mistral API**.
    -   *Roleplay Persona*: The bot acts as a sophisticated time-travel expert.
    -   *Context Aware*: Remembers your conversation history.
-   **Smooth Animations**: Scroll-triggered reveals and micro-interactions.

## Setup & Usage

1.  **Open the Project**: Simply open `timetravel-agency.html` in any modern web browser.
2.  **Explore**: Scroll through destinations and experiences.
3.  **Chat with Chronos**:
    -   Click the gold floating button in the bottom-right.
    -   Ask questions like *"What should I wear to 1889 Paris?"* or *"Is the timeline safe?"*.
    -   The responses are generated live by Mistral AI.

## Configuration

The project uses a hardcoded configuration for the Chatbot in the `timetravel-agency.html` script section:

```javascript
const API_KEY = "YOUR_MISTRAL_KEY"; // Currently set to a live key
const API_URL = "https://api.mistral.ai/v1/chat/completions";
```

> **Note**: For a production deployment, it is highly recommended to move the API Key to a backend server proxy to prevent exposure.

## Technologies

-   **HTML5 / CSS3** (Vanilla, no frameworks)
-   **JavaScript** (ES6+ Async/Await)
-   **Mistral AI API** (LLM Integration)

---

*Est. 2024 — Voyages Beyond Time.*
