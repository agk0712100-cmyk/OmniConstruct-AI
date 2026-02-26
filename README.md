# OmniConstruct AI: Vision-to-Live Autonomous Architect 🚀

OmniConstruct AI is a multimodal AI agent that transforms hand-drawn sketches into live, functional web applications on Google Cloud in seconds.

## 🌟 How it Works
1. **Visual Input:** User uploads a UI sketch.
2. **Gemini Vision Analysis:** The agent identifies components (Navbars, Buttons, Grids) using Gemini Live API.
3. **Autonomous Code Gen:** Gemini generates interactive Tailwind CSS and React-ready code.
4. **Cloud Deployment:** The backend orchestrates a deployment to **Google Cloud Run**.

## 🛠️ Technical Stack
* **LLM:** Gemini Live API (Multimodal)
* **Backend:** Python FastAPI (Running on GCP Cloud Run)
* **Frontend:** HTML5, Tailwind CSS, JavaScript
* **Infrastructure:** Google Cloud Build & Cloud Logging

## 🚀 Testing Instructions
1. Open the `index.html` file in any modern browser.
2. Upload a hand-drawn UI sketch (Sample provided in `/assets`).
3. Click 'EXECUTE LIVE BUILD' and watch the agent deploy the UI in real-time.
