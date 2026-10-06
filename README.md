# AI Resume Analyzer

Analyze a resume against a job description using the Gemini API.

## Setup

1. Create a Gemini API key in [Google AI Studio](https://aistudio.google.com/apikey).
2. Install the dependencies:

   ```powershell
   pip install -r requirements.txt
   ```

3. Create a `.env` file in this folder and add your key:

   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. Start the app:

   ```powershell
   streamlit run app.py
   ```

The app uses the `gemini-2.5-flash` model. API quotas and free-tier availability
depend on your Google AI Studio account. Do not share or commit your API key.