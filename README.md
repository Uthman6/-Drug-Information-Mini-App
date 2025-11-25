A simple, easy-to-use application that allows users to browse a list of drugs and view detailed information about each one.

📌 Project Overview

This mini app was developed to make drug information easily accessible.
Users can scroll through a list of drug names, and by clicking on any drug, the app displays detailed information such as its uses, dosage, side effects, and additional notes.

The goal of the project is to demonstrate how data can be collected, processed, stored, and deployed using modern no-code/low-code tools.

🛠️ Tools & Technologies Used
1. SQL (Data Generation)

Used SQL queries to generate, structure, and clean the initial drug dataset.

Ensured the data was well-formatted and consistent before exporting.

2. Google Sheets (Data Storage)

The cleaned SQL dataset was uploaded into Google Sheets.

The sheet acts as the backend database for the app.

3. AppSheet (App Development & Deployment)

Built the interactive mini app using AppSheet.

Features include:

List of drugs

Click-to-view detailed drug info

Responsive and mobile-friendly interface

AppSheet connects directly to Google Sheets for real-time updates.

4. Google Drive (Dataset Hosting)

Google Drive was used to store the dataset file before linking it to Google Sheets and AppSheet.

✨ Features

✅ Clean list of drug names
✅ Click on any drug to view full details
✅ Automatically updates when the dataset changes
✅ Deployed online using AppSheet
✅ Works on both desktop and mobile devices

📂 Project Structure
/dataset
    └── drugs_data.xlsx (Generated with SQL)

app/
    └── AppSheet Project Files
!{a display result}

🚀 How It Works

SQL was used to create the structured drug dataset.

The dataset was uploaded to Google Sheets for easy access and modification.

AppSheet reads the data from Google Sheets and generates an interactive UI.

The final app is deployed and accessible online.
