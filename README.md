<h1 align="center">🖼️ DALL·E Image Generator</h1>

<p align="center">
  A simple <b>Flask web app</b> that uses <b>OpenAI DALL·E</b> API to generate images from text prompts.  
  Type your imagination ✨ ➝ Get AI-generated images instantly 🎨
</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li>💡 <b>Text-to-Image</b>: Generate unique AI images with <code>DALL·E</code>.</li>
  <li>🌐 <b>Web Interface</b>: Built with <code>Flask</code> + <code>Bootstrap</code>.</li>
  <li>📦 <b>Multiple Images</b>: Get <b>5 variations</b> per prompt.</li>
  <li>⚡ <b>Live Preview</b>: See results instantly in your browser.</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>

<pre>
dalle-image-generator/
├── app.py             # Flask backend
├── index.html         # Frontend template
├── requirements.txt   # Dependencies
├── .gitignore
└── README.md
</pre>

<hr>

<h2>⚙️ Installation</h2>

<pre>
# Clone the repository
git clone https://github.com/your-username/dalle-image-generator.git
cd dalle-image-generator

# Create virtual environment
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
</pre>

<hr>

<h2>🔑 Setup</h2>
<p>Create a <code>.env</code> file in the root folder and add your OpenAI API key:</p>

<pre>
OPENAI_API_KEY=your_api_key_here
</pre>

<hr>

<h2>▶️ Run the App</h2>

<pre>
python app.py
</pre>

<p>Open in browser 👉 <a href="http://127.0.0.1:8080" target="_blank">http://127.0.0.1:8080</a></p>

<hr>

<h2>🖼️ Usage</h2>
<ol>
  <li>Enter a prompt (e.g., <code>a cat wearing sunglasses on the beach</code> 😎).</li>
  <li>Click <b>Submit</b>.</li>
  <li>Wait for a few seconds ⏳.</li>
  <li>See <b>5 AI-generated images</b> appear instantly!</li>
</ol>

<hr>

<h2>🙌 Credits</h2>

<p>
Created by <strong>Mehedi Hassan</strong> using <code>Flask</code>, and <code>OpenAI DALL·E API</code>. 
</p>

<hr>

<p align="center">⭐ Star this repo if you enjoy building AI-powered apps!</p>

