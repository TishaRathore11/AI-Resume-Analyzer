<p><small>Best View in <a href="https://github.com/settings/appearance">Light Mode</a> and Desktop Site (Recommended)</small></p><br/>

![AI-Resume-Analyzer](https://socialify.git.ci/TishaRathore11/AI-Resume-Analyzer/image?description=1&descriptionEditable=AI%2FML%20Project%20-%20Resume%20Parsing%2C%20Scoring%20%26%20Recommendation%20System&font=Raleway&language=1&pattern=Plus&theme=Light)

<div align="center">
  <h1>🌴 AI RESUME ANALYZER 🌴</h1>
  <p>A Tool for Resume Analysis, Predictions and Recommendations</p>
  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/github/last-commit/TishaRathore11/AI-Resume-Analyzer" alt="last update" />
    <img src="https://badges.frapsoft.com/os/v2/open-source.svg?v=103" alt="open source" />
    <img src="https://img.shields.io/github/languages/top/TishaRathore11/AI-Resume-Analyzer?color=red" alt="language" />
    <img src="https://img.shields.io/github/languages/code-size/TishaRathore11/AI-Resume-Analyzer?color=informational" alt="code size" />
    <a href="https://github.com/TishaRathore11/AI-Resume-Analyzer/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/TishaRathore11/AI-Resume-Analyzer.svg?color=yellow" alt="license" />
    </a>
  </p>

  <h4>
    <a href="#preview-">View Demo</a>
    <span> · </span>
    <a href="#setup--installation-">Installation</a>
  </h4>
  <p>
    <small align="justify">
      Built with 🤍 by
      <a href="https://github.com/TishaRathore11">Tisha Rathore</a>
     </small>
  </p>
  <small align="justify">🚀 A Project built as part of B.Tech (ECE - AI/ML & Data Science) coursework
  </small>
</div><br/><br/>

## About the Project 🥱
<div align="center">
    <p align="justify">
      A tool which parses information from a resume using natural language processing and finds the keywords, clusters them into sectors based on their keywords.
      And lastly shows recommendations, predictions, and analytics to the applicant based on keyword matching.
    </p>
</div>

## Scope 😲
i. It can be used for getting all the resume data into a structured tabular format and csv as well, so that the organization can use this data for analytics purposes

ii. By providing recommendations, predictions and an overall score, the user can improve their resume and keep testing it on the tool

iii. It can be used by colleges to get insight into students and their resumes before placements

iv. Also, to get analytics on the roles users are mostly looking for

v. To improve this tool by collecting feedback

<!-- TechStack -->
## Tech Stack 🍻
<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/HTML">HTML</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript">JavaScript</a></li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://www.python.org/">Python</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mysql.com/">MySQL</a></li>
  </ul>
</details>

<details>
<summary>Modules</summary>
  <ul>
    <li><a href="https://pandas.pydata.org/">pandas</a></li>
    <li><a href="https://github.com/OmkarPathak/pyresparser">pyresparser</a></li>
    <li><a href="https://pypi.org/project/pdfminer3/">pdfminer3</a></li>
    <li><a href="https://plotly.com/">Plotly</a></li>
    <li><a href="https://www.nltk.org/">NLTK</a></li>
  </ul>
</details>

<!-- Features -->
## Features 🤦‍♂️
### Client: -
- Fetching Location and Miscellaneous Data

  Using Parsing Techniques to fetch
- Basic Info
- Skills
- Keywords

Using logical programs, it will recommend
- Skills that can be added
- Predicted job role
- Course and certificate suggestions
- Resume tips and ideas
- Overall Score
- Interview & Resume tip videos

### Admin: -
- Get all applicants' data into tabular format
- Download users' data into a csv file
- View all saved uploaded pdfs in the Uploaded Resume folder
- View user feedback and ratings

  Pie Charts for: -
- Ratings
- Predicted field / roles
- Experience level
- Resume score
- User count
- City
- State
- Country

### Feedback: -
- Form filling
- Rating from 1 – 5
- Overall ratings pie chart
- Past user comment history

## Requirements 😅
### Have these installed to make your setup smooth
1) Python (3.9.12) https://www.python.org/downloads/release/python-3912/
2) MySQL https://www.mysql.com/downloads/
3) Visual Studio Code **(Preferred Code Editor)** https://code.visualstudio.com/Download
4) Visual Studio build tools for C++ https://aka.ms/vs/17/release/vs_BuildTools.exe

## Setup & Installation 👀

To run this project, perform the following steps 😨

Download the code manually or via git
```bash
git clone https://github.com/TishaRathore11/AI-Resume-Analyzer.git
```

Create a virtual environment and activate it **(recommended)**

Open your command prompt, change your project directory to ```AI-Resume-Analyzer``` and run
```bash
python -m venv venvapp

cd venvapp/Scripts

activate

```

Install packages from ```requirements.txt``` inside the ``App`` folder
```bash
cd../..

cd App

pip install -r requirements.txt

python -m spacy download en_core_web_sm

```

After installation is finished, create a database named ```cv```

Then update your DB credentials inside ```App.py``` (search for the `pymysql.connect(...)` line near the top of the file)

Go to the ```venvapp\Lib\site-packages\pyresparser``` folder

And replace ```resume_parser.py``` with the ```resume_parser.py```

provided inside the ```pyresparser``` folder of this repo

``Your setup 👆 and installation is finished 😵🤯``

Make sure your ``venvapp`` is activated and your working directory is inside ``App``

Run the app using
```bash
streamlit run App.py

```

## Known Error 🤪
If a ``GeocoderUnavailable`` error comes up, check your internet connection and network speed.

## Usage
- Once set up, everything runs automatically
- Just upload a resume and let the tool do its thing
- Try it first with a sample resume in the ``Uploaded_Resumes`` folder
- Admin login credentials are set in ```App.py``` (update them there for your own use)

<!-- Roadmap -->
## Roadmap 🛵
* [x] Predict user experience level.
* [x] Add resume scoring criteria for skills and projects.
* [x] Added fields and recommendations for web, android, ios, data science.
* [x] Custom UI theme and styling.
* [ ] Add more fields for other roles, and their respective recommendations.
* [ ] View individual user details.

## Contributing 🤘
Pull requests are welcome.

For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgement 🤗
- <a href="https://www.academia.edu/32543544/Resume_Parser_with_Natural_Language_Processing">Resume Parser with Natural Language Processing</a>
- <a href="https://github.com/OmkarPathak/pyresparser">pyresparser</a>

## Preview 👽

### Client Side

**Main Screen**

![Screenshot](screenshots\main_screen.png)

**Resume Analysis**

![Screenshot](screenshots\resume_analysis.png)

**Skill Recommendation**

![Screenshot](screenshots\skill recommendation.png)

**Course Recommendation**

![Screenshot](screenshots\course_recommendation.png)

**Tips and Overall Score**

![Screenshot](screenshots\resume_score.png)

**Video Recommendation**

![Screenshot](screenshots\video_recommendation.png)

### Feedback

**Feedback Form**

![Screenshot](screenshots\feedback.png)

### Admin

**Login**

![Screenshot](screenshots\admin.png)

**Exported csv file**

![Screenshot](screenshots\csv.png)


**Pie Chart Analytical Representation of Clusters**

![Screenshot](screenshots\Screenshot 2026-07-25 010950.png)

![Screenshot](screenshots\Screenshot 2026-07-25 011005.png)

### Built with 🤍 by <a href="https://github.com/TishaRathore11">Tisha Rathore</a>
