# Identification of Training Patterns for Race Preparation

Name: Mark Kennedy, Student Number: 15312186, Email: mark.kennedy.3@ucdconnect.ie

Supervisor: Dr. Aonghus Lawlor, Email: aonghus.lawlor@ucd.ie

## Project Objectives
* Core: Identify the most important feature(s) for an athlete to focus on when training for a marathon.

* Core: Determine the most suitable way to categorise the different approaches taken by athletes when preparing for a marathon, and to determine which approach is the most efficient.

* Advanced: Build a recommender model capable of recommending new training targets for individual athletes, based on their completed sessions to-date. These targets will help the athletes to achieve their desired finish time in the eventual marathon race.

## How To Run Notebooks

Important Note: The project supervisor has access to the raw dataset, you will have to seek permission from him in order to gain access to it and to subsequently run these notebooks. You can contact him at the email address provided above.

Step 1: Download project folder from github.

Step 2: Install environment packages.

```bash
pip install requirements.txt
```

Step 3: Run the notebooks in numerical order. (e.g. 000,100,200,300,400)

## Links To Notebooks:
### Data Preperation:
* [000_Prepare_Data](notebooks/000_Prepare_Data.ipynb)
### Time Series Classification
* [100_Dynamic_Time_Warping](notebooks/100_Dynamic_Time_Warping.ipynb)
* [200_Feature_Extraction_&_Clustering](notebooks/200_Feature_Extraction_&_Clustering.ipynb)
### Core: Cluster Analysis
* [300_Cluster_Analysis](notebooks/300_Cluster_Analysis.ipynb)
### Advanced: Training Targets Recommender
* [400_Advanced](notebooks/400_Advanced.ipynb)
