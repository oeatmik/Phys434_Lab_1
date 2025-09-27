# PHYS 434 A Au 25: Advanced Laboratory: Computational Data Analysis

**Lab Sections (B143)**  
Tuesday (AA) 1:30-4:20  
**Instructor:** Linda Zhenyu Jin (<lindajin@uw.edu>)

## Course Overview

This repository contains laboratory notebooks and datasets for Physics 434, focusing on computational data analysis techniques using real astronomical data, particularly pulsar survey data from the High Time Resolution Universe Survey (HTRU2).

## Repository Contents

- `lab_1_template.ipynb` - Template notebook for Lab 1: Statistical Analysis and Data Visualization
- `htru2/` - Contains the HTRU2 dataset for pulsar analysis
- Lab instructions and datasets for computational data analysis

## Getting Started

### Option 1: Local Setup (VS Code)

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Klinjin/Au25_Phys434_Data_Analysis_Lab.git
   cd Au25_Phys434_Data_Analysis_Lab
   ```

2. **Install Python dependencies:**
   ```bash
   pip install pandas matplotlib numpy scipy jupyter
   ```

3. **Open in VS Code:**
   - Install the Python and Jupyter extensions in VS Code
   - Open the repository folder in VS Code
   - Click on any `.ipynb` file to start working with notebooks

### Option 2: Local Setup (Browser Terminal)

1. **Clone and navigate to repository:**
   ```bash
   git clone https://github.com/[YOUR_USERNAME]/Au25_Phys434_Data_Analysis_Lab.git
   cd Au25_Phys434_Data_Analysis_Lab
   ```

2. **Install dependencies and start Jupyter:**
   ```bash
   pip install pandas matplotlib numpy scipy jupyter
   jupyter notebook
   ```

3. **Access notebooks:**
   - Your browser will open automatically
   - Navigate to the notebook files (`.ipynb`) to start working

### Option 3: Google Colab

1. **Upload to Google Drive:**
   - Download or clone this repository
   - Upload the entire folder to your Google Drive

2. **Open in Colab:**
   - Go to [Google Colab](https://colab.research.google.com/)
   - Click "File" → "Open notebook" → "Google Drive"
   - Navigate to your uploaded repository folder
   - Select the notebook you want to work with

3. **Mount Google Drive (run this in the first cell):**
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   %cd /content/drive/MyDrive/[YOUR_REPOSITORY_FOLDER]
   ```

## Lab Requirements

- **Python 3.7+**
- **Required packages:** pandas, matplotlib, numpy, scipy
- **Dataset:** HTRU2 pulsar survey data (included in repository)

## Data Analysis Topics

- Statistical analysis and probability calculations
- Bayes' theorem applications
- Data visualization with histograms
- Normal distribution analysis
- p-value calculations and hypothesis testing

## Submission Guidelines

1. Complete the notebook templates by filling in the TODO sections
2. Ensure all cells run without errors
3. Include clear documentation and interpretations
4. Commit your completed work to your GitHub repository
5. Share your repository link for grading

## Getting Help

- **Office Hours:** Contact instructor via email
- **Course Resources:** See Canvas for additional materials
- **Technical Issues:** Ensure all dependencies are installed correctly

## Academic Integrity

Please complete your own work. You may discuss concepts with classmates, but your code and analysis should be your own.

---

*Last updated: September 2025*