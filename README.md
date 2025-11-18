# AI Health & Fitness Planner Agent 🏋️‍♂️

The **AI Health & Fitness Planner** is a personalized health and fitness Agent powered by Agno AI Agent framework. This app generates tailored dietary and fitness plans based on user inputs such as age, weight, height, activity level, dietary preferences, and fitness goals.

## Features

- **Health Agent and Fitness Agent**
    - The app has two phidata agents that are specialists in giving Diet advice and Fitness/workout advice respectively.

- **Personalized Dietary Plans**:
  - Generates detailed meal plans (breakfast, lunch, dinner, and snacks).
  - Includes important considerations like hydration, electrolytes, and fiber intake.
  - Supports various dietary preferences like Keto, Vegetarian, Low Carb, etc.

- **Personalized Fitness Plans**:
  - Provides customized exercise routines based on fitness goals.
  - Covers warm-ups, main workouts, and cool-downs.
  - Includes actionable fitness tips and progress tracking advice.

- **Interactive Q&A**: Allows users to ask follow-up questions about their plans.


## Requirements

The application requires the following Python libraries:

- `agno`
- `google-generativeai`
- `streamlit`

Ensure these dependencies are installed via the `requirements.txt` file according to their mentioned versions

## How to Run

Follow the steps below to set up and run the application:

### Prerequisites
Get a free Gemini API Key from Google AI: https://aistudio.google.com/apikey

### Local Development

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
   cd advanced_ai_agents/single_agent_apps/ai_health_fitness_agent
   ```

2. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up your API key**:
   ```bash
   export GEMINI_API_KEY="your_gemini_api_key_here"
   ```

4. **Run the Streamlit app**:
    ```bash
    streamlit run health_agent.py
    ```

### Deploy to Streamlit Cloud

1. **Fork this repository** to your GitHub account
2. **Go to [Streamlit Cloud](https://share.streamlit.io/)**
3. **Deploy your app** by connecting your GitHub repository
4. **Add your API key** in the app settings:
   - Go to your app's settings
   - Navigate to the "Secrets" section
   - Add: `GEMINI_API_KEY = "your_api_key_here"`

### Environment Variables

The app will automatically detect and use:
- `GEMINI_API_KEY`: Your Google Gemini API key
- Streamlit Cloud secrets (when deployed)


