# CareerPrep AI: Disha AI

## Overview
**CareerPrep AI** **-** **Disha AI**) is an advanced, unified career recommendation platform designed to align academic profiles with current industry demands. Developed at **Vimal Jyothi Engineering College**, the system utilizes **XGBoost** and **Natural Language Processing (NLP)** to provide students and job seekers with personalized career paths, job matches, and educational course suggestions.

## Key Features
* **Predictive Career Matching:** Uses a custom XGBoost-based machine learning model to analyze user skills, education, and experience for high-accuracy job and course predictions.
* **Resume Optimization:** Includes an integrated CV generator and resume optimizer to improve candidate profiles for better market visibility.
* **Interview & Exam Prep:** Provides AI-driven mock interviews with real-time feedback, sample Q&A pairs, and exam preparation tools.
* **Market Intelligence:** Offers real-time salary comparisons and industry trend analysis to help users understand the evolving job market.
* **Dynamic Shortlisting:** Features a cloud-based Android application that uses Firebase Cloud Functions for automated job and course assignments.

## Technical Architecture
* **Machine Learning Engine:** Built on the **XGBoost** algorithm, demonstrating high performance with an **AUC of 0.95**, outperforming standard models like SVM (0.83).
* **Backend & Cloud:** Powered by **Firebase** for authentication, real-time database management, and serverless Cloud Functions.
* **Frontend:** A scalable **Android Application** providing a seamless mobile experience for profile management and progress tracking.
* **Data Processing:** Utilizes `LabelEncoder` and `replace` techniques for preprocessing user inputs and industry data into specialized categories.

## System Components
* **User Module:** Profile creation, resume uploading, and skill/interest preference selection.
* **Recommendation Engine:** Filters and ranks opportunities based on predicted "best-fit" scores.
* **Mock Interview Module:** Deep learning-based real-time practice sessions with difficulty-graded topics (e.g., Motivation, Technical Background).
* **Industry Dashboard:** Visualizations of salary ranges for roles like Software Engineer, Data Scientist, and Project Manager.

## Software Requirements
* **Programming Language:** Python
* **Cloud Platform:** Firebase (Authentication, Database, Functions)
* **Frameworks/Libraries:** XGBoost, Scikit-learn (LabelEncoder), NLP libraries, Android SDK

## Credits
* **Project Team:** Denise Maria James, Jyothika J, Litty Flowery Xavier, and Arya P.
* **Guidance:** Ms. Sarannya M, Assistant Professor, Dept. of ADS.
