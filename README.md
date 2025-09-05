# Digital Upasthiti - [AI Attendence System]
## DL Project - Class FR

Semi-Automated, Fully Automated


## Setting Up
1. Set the config.py in src folder
2. Install `requirements.txt` 

## To Run 
1. `cd src`
2. `streamlit run gui/main_upload_streamlit.py` To run Streamlit GUI Server
3. `streamlit run gui/main_streamlit.py` To run Streamlit GUI Server (without recognition, just to view results.json)


## Analysis
1. `python main.py` for batch processing (change folder name)
2. `python merge_attendance.py`to generate final csv with 'A' and 'P'

## Folder Description
- assets - for github assets
- data 
    - GT images - for generating features
    - student_list.csv - for final results prepration
    - pkl file of features
    - students_details.json
- extra - extra stuff and past data, for future use
- RECORDS - to contain evaluation photos, results
- run_files - temporary files, folders for intermediate data
- src - containing source code

## Plots
![image](assets/plots.png)

## Flow Chart
![image](assets/flow_chart.png)


# Screenshots
![image](assets/demo.png)


## Credits
- Vinay 
- Meet
- Pranjal