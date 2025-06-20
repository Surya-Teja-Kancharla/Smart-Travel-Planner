<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Smart Travel Planner - A web application for planning trips using weather data, feature engineering, and KNN classifier predictions.">
</head>
<body>
    <div class="container">
        <h1>Smart Travel Planner</h1>
        <p>
            Smart Travel Planner is a web application that helps users plan their trips by providing relevant insights based on weather data, feature engineering, and predictions using a KNN classifier.
        </p>
        <h2>Features</h2>
        <ul>
            <li>Integrates weather data from 22 famous tourist destibnationsacross the world.</li>
            <li>Preprocessed and feature-engineered data for better insights.</li>
            <li>Predictive analysis for travel planning using a KNN classifier.</li>
            <li>User-friendly web interface built with Streamlit.</li>
        </ul>
        <h2>Live Application</h2>
        <p>
            You can access the live application here: 
            <a href="https://smart-travel-planner-7apjk7tr63xwwcjd7e2v7z.streamlit.app/" target="_blank">
                Smart Travel Planner
            </a>
        </p>
        <h2>How to Run Locally</h2>
        <ol>
            <li>Clone this repository:
                <pre>git clone https://github.com/Surya-Teja-Kancharla/Smart-Travel-Planner.git</pre>
            </li>
            <li>Navigate to the project directory:
                <pre>cd Smart-Travel-Planner</pre>
            </li>
            <li>Install dependencies:
                <pre>pip install -r requirements.txt</pre>
            </li>
            <li>Run the application:
                <pre>streamlit run app.py</pre>
            </li>
            <li>Open your browser and navigate to <code>http://localhost:8501</code>.</li>
        </ol>
        <h2>Technologies Used</h2>
        <ul>
            <li><strong>Python</strong></li>
            <li><strong>Streamlit</strong></li>
            <li><strong>KNN Classifier</strong></li>
            <li><strong>Weather API Integration</strong></li>
            <li><strong>Data Preprocessing and Feature Engineering</strong></li>
        </ul>
        <h2>Folder Structure</h2>
        <ul>
            <li><code>app.py</code>: Main application script.</li>
            <li><code>data/</code>: Contains data files used for predictions.</li>
            <li><code>requirements.txt</code>: List of Python dependencies.</li>
            <li><code>README.md</code>: Documentation.</li>
        </ul>
        <h2>Contributing</h2>
        <p>
            Feel free to submit issues or pull requests to contribute to the project.
        </p>
        <h2>License</h2>
        <p>
            This project is licensed under the <a href="LICENSE">MIT License</a>.
        </p>
        <hr>
        <p>
            Developed by <a href="https://github.com/Surya-Teja-Kancharla" target="_blank">Surya Teja Kancharla</a>.
        </p>
    </div>
</body>
</html>
