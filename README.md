<h1>📘 Learn NumPy using Python, Jupyter Lab</h1>

<p>In this repo, we are learning <strong>NumPy</strong> and working with <strong>Jupyter Lab</strong> using a custom <code>venv</code> environment.  
We also install <strong>Python 3.13.3</strong>, <strong>pip 25.1.1</strong>, and required packages inside the virtual environment.</p>

<p>To run this project correctly, please follow the steps below.</p>

<hr />

<h2>✅ Setup Steps</h2>

<ol>
  <li><strong>Install Python 3.13.3</strong><br />
    - Download from: <a href="https://www.python.org/downloads/release">https://www.python.org/downloads/release</a><br />
    - During installation, make sure to <strong>check "Add Python to PATH"</strong>
  </li>

  <li><strong>Open CMD or Terminal</strong><br />
    Navigate to the folder where you pasted or cloned this project:
    <pre><code>cd your-project-folder</code></pre>
  </li>

  <li><strong>Create a new virtual environment</strong><br />
    <pre><code>python -m venv venv</code></pre>
    This will create a <code>venv</code> folder in your current directory.
  </li>

  <li><strong>Activate the virtual environment</strong><br />
    <ul>
      <li><strong>Windows:</strong><br />
        <code>venv\Scripts\activate</code>
      </li>
      <li><strong>macOS/Linux:</strong><br />
        <code>source venv/bin/activate</code>
      </li>
    </ul>
    After activation, your command line should show: <code>(venv)</code>
  </li>

  <li><strong>Upgrade pip to version 25.1.1</strong><br />
    <pre><code>pip install --upgrade pip==25.1.1</code></pre>
  </li>

  <li><strong>Install Jupyter Lab</strong><br />
    <pre><code>pip install jupyterlab</code></pre>
  </li>

  <li><strong>Install NumPy</strong><br />
    <pre><code>pip install numpy</code></pre>
  </li>

  <li><strong>Run Jupyter Lab</strong><br />
    <pre><code>jupyter lab</code></pre>
    This will open Jupyter Lab in your browser automatically.
  </li>
</ol>

<hr />

<h2>📂 Project Folder Structure</h2>

<pre><code>your-project-folder/
│
├── notebooks/            → Jupyter notebooks using NumPy
├── .gitignore            → Ignore venv, __pycache__, etc.
├── README.md             → This file
└── venv/                 → (Created locally, NOT included in repo)</code></pre>

<hr />

<h2>💡 Notes</h2>

<ul>
  <li>Always activate your virtual environment before running commands.</li>
</ul>

<hr />

<h2>🚀 You're Ready!</h2>

<p>Now you're ready to explore and learn NumPy, and build Jupyter Lab notebooks in a clean virtual environment. Happy coding! 🧠✨</p>
