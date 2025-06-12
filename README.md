# Port-Scanner
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Python Port Scanner</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0f1117;
      color: #e4e4e4;
      margin: 0;
      padding: 2rem;
    }

    h1, h2 {
      color: #00ffae;
    }

    code {
      background-color: #1e1e2f;
      color: #c0ffee;
      padding: 0.2em 0.4em;
      border-radius: 4px;
      font-size: 0.95em;
    }

    pre {
      background-color: #1e1e2f;
      color: #f5f5f5;
      padding: 1em;
      border-radius: 6px;
      overflow-x: auto;
    }

    .badge {
      display: inline-block;
      margin-right: 10px;
      margin-bottom: 5px;
    }

    a {
      color: #00f7ff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .section {
      margin-top: 2rem;
    }

    ul {
      line-height: 1.7;
    }

    .screenshot {
      margin-top: 1rem;
      border-radius: 10px;
      max-width: 100%;
      height: auto;
      border: 1px solid #555;
    }

    .footer {
      margin-top: 3rem;
      font-size: 0.9em;
      color: #aaa;
    }
  </style>
</head>
<body>

  <h1>🔍 Python Port Scanner</h1>
  <div class="badge">
    <img src="https://img.shields.io/badge/Python-3.x-blue.svg" alt="Python">
    <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
    <img src="https://img.shields.io/badge/Status-Active-success.svg" alt="Status">
  </div>

  <div class="section">
    <h2>🛠 Features</h2>
    <ul>
      <li>Scan a target host for open TCP ports</li>
      <li>Customizable port ranges</li>
      <li>Fast and efficient using sockets</li>
      <li>Clean, readable terminal output</li>
      <li>Cross-platform: Windows, Linux, macOS</li>
    </ul>
  </div>

  <div class="section">
    <h2>📁 Project Structure</h2>
    <pre>
port_scanner/
├── portscanner.py        # Main script
├── README.html           # This file
└── requirements.txt      # Dependencies (if any)
    </pre>
  </div>

  <div class="section">
    <h2>🚀 Getting Started</h2>
    <h3>🔧 Prerequisites</h3>
    <p>Python 3.x installed on your system</p>

    <h3>📦 Installation</h3>
    <pre>
git clone https://github.com/yourusername/port_scanner.git
cd port_scanner

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
    </pre>
  </div>

  <div class="section">
    <h2>▶️ Usage</h2>
    <pre>
python portscanner.py 192.168.1.1 1 1024
    </pre>
    <p>Arguments:</p>
    <ul>
      <li><code>target IP</code> – IP address to scan</li>
      <li><code>start_port</code> – starting port number</li>
      <li><code>end_port</code> – ending port number</li>
    </ul>
  </div>

  <div class="section">
    <h2>📸 Screenshot</h2>
    <p>Add a screenshot here to show it in action:</p>
    <img src="your-screenshot.png" alt="Port Scanner Screenshot" class="screenshot">
  </div>

  <div class="section">
    <h2>📜 License</h2>
    <p>This project is licensed under the <strong>MIT License</strong> — see the <code>LICENSE</code> file for details.</p>
  </div>

  <div class="section">
    <h2>🙋‍♂️ Author</h2>
    <p><strong>Lucifer</strong><br>
    💻 Ethical Hacker & Python Developer<br>
    📫 Connect:
      <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a> |
      <a href="https://github.com/yourusername" target="_blank">GitHub</a>
    </p>
  </div>

  <div class="footer">
    &copy; 2025 Lucifer. All rights reserved.
  </div>

</body>
</html>
