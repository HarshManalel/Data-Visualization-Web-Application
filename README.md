# 📊 Data Visualization Tool: Generating and Storing Visualizations

This is a Flask-based data visualization tool that generates and stores 6 headings with 4 types of visualizations for each heading. The visualizations are stored in 6 separate folders within the `static` folder and can be accessed from there. The tool uses the following headings and data to create the visualizations:


## Headings Data Details 💻

- Name
- Age (number from 1-50)
- Gender (male and female)
- Device used (laptops, mobiles, tablets, pcs)
- Network used (2g, 3g, 4g, 5g)

The visualizations are created using Matplotlib, Seaborn or any other suitable libraries, and saved as .jpg files in their respective folders. The tool also integrates with Bootstrap and jQuery for designing, and uses real-time data collection through a form that is integrated with Flask. Results are stored and processed using WiFi captive tunneling (MypUBLIC WIFI) and a PDF download option is provided to users so that they can download the plots they generated.


## Tools Details 👩‍💻
| Tool/Technology | Description                   | Software Used            | Skills Gained                  |
|-----------------|-------------------------------|--------------------------|--------------------------------|
| Flask           | Python web framework          | Python                   | Web development                |
| Matplotlib      | Data visualization library    | Python                   | Data visualization             |
| Seaborn         | Data visualization library    | Python                   | Data visualization             |
| Bootstrap       | Front-end framework           | HTML, CSS, JavaScript    | Web development                |
| jQuery          | JavaScript library            | JavaScript               | Web development                |
| Gensim          | NLP package                   | Python                   | Natural language processing    |
| SpaCy           | NLP package                   | Python                   | Natural language processing    |
| Pandas          | Data manipulation library     | Python                   | Data manipulation              |


## Installation

1. Clone the repository
2. Install the necessary packages using pip: `pip install -r requirements.txt`
3. Run the Flask application: `python app.py`

## Usage  🔥

1. Navigate to `localhost:5000` on your web browser
2. Fill out the form with your data
3. Click on the "Generate Visualizations" button
4. The visualizations will be generated and stored in their respective folders within the `static` folder
5. To download a PDF version of the visualization, click on the "Download as PDF" button
