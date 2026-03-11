# Multi-Agent-Hospitality-Planner
Powered by AI Researcher &amp; Writer Agents — crafting your perfect trip
# 🌍 Multi-Agent Hospitality Planner
A premium travel planning system powered by **CrewAI** and **Google Gemini**. This application uses autonomous AI agents to research, plan, and format high-quality travel itineraries tailored to your destination, duration, and budget.
![App Screenshot](<img width="1918" height="905" alt="image" src="https://github.com/user-attachments/assets/94d3df59-50f6-49ed-8e5e-5a9389a6ba37" />
)
## 🚀 Key Features
-   **Deep Travel Research**: Autonomous agents search for famous landmarks, hidden gems, and localized activities.
-   **Budget-Aware Planning**: Support for **Low**, **Moderate**, and **High** budget levels with appropriate recommendations.
-   **Day-by-Day Structure**: Beautifully formatted markdown itineraries including morning, afternoon, and evening plans.
-   **AI Image Generation**: Visualizes your destination using Imagen 3.0 (or Unsplash fallback).
-   **Exportable Content**: Save your itineraries as Markdown files for offline use.
-   **Dual Interface**: Run as a modern **Streamlit Web App** or a rapid **CLI Tool**.
## 🤖 The AI Crew
The system utilizes a specialized crew of two agents:
1.  **🔍 Senior Travel Researcher**: An expert consultant specialized in logistics, local secrets, and high-value accommodations.
2.  **✍️ Travel Itinerary Writer**: A renowned travel blogger skilled at synthesizing data into luxurious, easy-to-read guides.
## 🛠️ Setup & Installation
### Prerequisites
-   Python 3.10 or higher
-   A Google Gemini API key ([Get one here](https://aistudio.google.com/))
### Installation
1.  **Clone the project** to your local machine.
2.  **Create a virtual environment**:
    ```bash
    python -m venv .venv
    ```
3.  **Activate the environment**:
    -   *Windows*: `.venv\Scripts\activate`
    -   *Mac/Linux*: `source .venv/bin/activate`
4.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
### Configuration
Create a `.env` file in the root directory and add your API credentials:
```env
GEMINI_API_KEY=your_api_key_here
CREW_TRACING_ENABLED=true
## 🎮 How to Run
### 1. Web Application (Recommended)
Launch the interactive Streamlit dashboard for the full visual experience:
```bash
streamlit run app.py
*Or use the provided PowerShell launcher:* `./run.ps1`

### 2. Command Line Interface
For quick generations without a browser:
```bash
python main.py
```

## 🏗️ Project Structure
-   `app.py`: Main Streamlit application with rich UI and image generation.
-   `main.py`: CLI-based entry point for the agent crew.
-   `agents.py`: CrewAI agent definitions and LLM configuration.
-   `tasks.py`: Structured task definitions for research and formatting.
-   `requirements.txt`: Project dependencies.

