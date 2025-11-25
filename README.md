A simple, interactive application that allows users to browse and search drug names by category, then click on any drug to view full details.

📌 Project Overview

This mini app was created to make drug information easy to find and understand.
Users can browse drugs, filter by category, search for medicines by name, and view complete drug details such as uses, dosage, and side effects.

The project demonstrates how SQL, Google Sheets, and AppSheet can work together to build a clean, functional health information tool.

🛠️ Tools & Technologies Used
1. SQL (Data Generation)

Structured and cleaned drug data using SQL.

Added a category field for each drug (e.g., antibiotics, analgesics, antihistamines, etc.).

2. Google Sheets (Data Storage)

Served as the backend database.

Contains drug name, category, details, side effects, dosage, and more.

3. AppSheet (App Development & Deployment)

Used to build the app interface.

Key features include:

Drug list

Drug categories

Search bar for quick lookup

Filter drugs by category

Click-to-view drug information

Real-time connection to Google Sheets

Mobile-friendly interface

Additional improvements added later

4. Google Drive (Dataset Hosting)

Used to upload and manage the dataset files.

✨ Features

✅ List of drug names
✅ Categories (e.g., Antibiotics, Painkillers, Antimalarials, etc.)
✅ Filter drugs by category
✅ Search drug names quickly
✅ Click to view full information
✅ Automatically updates from Google Sheets
✅ Smooth UI on web and mobile
✅ Later improvements added for better navigation and layout

📂 Project Structure
/dataset
    └── drugs_data.xlsx

app/
    └── AppSheet Project Files

README.md

🚀 How It Works

SQL used to generate and categorize drug data.

Data uploaded to Google Sheets.

AppSheet connects and builds the UI.

Users can:

Browse drugs by category

Search for any medicine

Click to view full drug details

Additional improvements added later for smoother experience.

📈 Future Improvements

Add icons or images for each category

Add sub-categories (e.g., painkillers → NSAIDs, opioids)

Add dosage calculators

Allow users to bookmark favorite drugs
