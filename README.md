# Reddit_persona_Generator
<b>Overview</b> <br>
The Reddit Persona Generator is a tool that scrapes a Reddit user's posts and comments using a provided profile URL and analyzes them with the Gemini API to create a detailed user persona. This project is ideal for researchers, marketers, or developers interested in understanding user behavior and characteristics based on their Reddit activity.

Features <br>
<ul>
<li>Scrapes Reddit user posts and comments using a provided profile URL.</li>
<li>Analyzes scraped data with the Gemini API to generate a user persona.</li>
<li>Outputs a structured persona summarizing the user's interests, tone, and activity patterns.</li>
<li>Easy-to-configure setup for developers to extend or modify.</li>
</ul>

<b>Prerequisites</b>
<br>
<ul>
<li>Python 3.8+ installed on your system.</li>
<li>Jupyter Notebook or JupyterLab installed.</li>
<li>A Reddit account(https://www.reddit.com/prefs/apps).</li>
<li>A Gemini API key from Google AI Studio.(https://aistudio.google.com/app/apikey)</li>
<li>Basic familiarity with Python, Git, Jupyter notebooks, and command-line interfaces.</li>
</ul>

<b>Setup Instructions</b>
<ul>
  <li>Clone the repository</li>
  <li>Install required libraries(ex. praw google-generativeai)</li>
  <li>Create a env.text in same folder as reddit.ipynb. Replace your keys with this
    REDDIT_CLIENT_ID=your-client-id
    REDDIT_CLIENT_SECRET=your-client-secret
   GEMINI_API_KEYT=your key
 </li>
  <li>Provide url in the format (ex. Reddit URL: https://www.reddit.com/user/lucasmellor)</li>
</ul>
<p>Outputs have been shared in this repository inside samples folder</p>
