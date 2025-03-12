<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MedIA-Witch</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #181818;
            color: #fff;
            margin: 0;
            padding: 0;
        }

        h1, h2, h3 {
            color: #ff7f00;
        }

        p, ul {
            color: #ccc;
        }

        a {
            color: #ff7f00;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        .section {
            margin-bottom: 40px;
        }

        .screenshot img, .logo img, .comparison img {
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            display: block;
            border-radius: 10px;
        }

        .comparison {
            display: flex;
            justify-content: space-between;
        }

        .comparison div {
            width: 48%;
        }

        .comparison img {
            border-radius: 10px;
        }

        .btn {
            background-color: #ff7f00;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        .btn:hover {
            background-color: #e56b00;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #222;
            color: #fff;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <div class="container">
        <header class="header">
            <h1>MedIA-Witch</h1>
            <h3>AI-Based Image and Video Enhancement Tool</h3>
            <p><a href="https://drive.google.com/file/d/1CnmoM4tFXdS3KpNSUvMAOXNhSdAtIwan/view?usp=sharing" class="btn">Click here to download the .exe installer from Google Drive</a></p>
        </header>

        <section class="section">
            <h2>🌟 Key Features</h2>
            <ul>
                <li><strong>Advanced AI Models for Quality Enhancement</strong>: Real-ESRGAN, SRGAN, BSRGAN, IRCNN.</li>
                <li><strong>Batch Processing</strong>: Enhance multiple images and videos simultaneously.</li>
                <li><strong>Customizable Settings</strong>: Adjust output resolution, formats, and AI model selection.</li>
                <li><strong>User-Friendly Interface</strong>: Easy to use for everyone.</li>
                <li><strong>Open-Source</strong>: MedIA-Witch is under the MIT License.</li>
            </ul>
        </section>

        <section class="section screenshot">
            <h2>📸 Screenshot</h2>
            <img src="Assets/Capture.png" alt="Screenshot of MedIA-Witch">
        </section>

        <section class="section comparison">
            <h2>🔍 Quality Comparison</h2>
            <div>
                <h3>Original Image</h3>
                <img src="Assets/OriginalImage.png" alt="Original Image">
            </div>
            <div>
                <h3>Enhanced Image (IRCNN_Mx1_fp16)</h3>
                <img src="Assets/UpscalerImage.png" alt="Enhanced Image">
            </div>
        </section>

        <section class="section">
            <h2>🚀 Installation</h2>
            <p>Follow these steps to get started with <strong>MedIA-Witch</strong>:</p>
            <ol>
                <li>Run the installer and follow the on-screen instructions.</li>
                <li>Launch the application by running MedIA-Witch.exe.</li>
                <li>Start enhancing your images and videos!</li>
            </ol>
        </section>

        <section class="section">
            <h2>📜 Credits and License</h2>
            <p>MedIA-Witch is based on several open-source technologies, including:</p>
            <ul>
                <li><a href="https://github.com/Djdefrag/QualityScaler.git">QualityScaler</a> (MIT License)</li>
                <li><a href="https://github.com/xinntao/Real-ESRGAN">Real-ESRGAN</a> (MIT License)</li>
                <li><a href="https://arxiv.org/abs/1609.04802">SRGAN</a> (MIT License)</li>
                <li><a href="https://arxiv.org/abs/1901.05324">BSRGAN</a> (MIT License)</li>
                <li><a href="https://github.com/lipengFu/IRCNN.git">IRCNN</a> (MIT License)</li>
            </ul>
            <p>MedIA-Witch is distributed under the MIT License. Please refer to the LICENSE file for more details.</p>
        </section>

        <footer>
            <p>&copy; 2025 MedIA-Witch. All rights reserved.</p>
        </footer>
    </div>

</body>
</html>
