# 🌌 Space Exploration Workflow

## 🔗 Live Webpage

https://starlight-gather.lovable.app/

## 📌 Project Description

This project is an automated space exploration workflow built using n8n.

The webpage is designed with a space theme and allows users to subscribe by submitting their basic details:

* Name
* Age
* Email Address

Once a user subscribes, their information is stored in Google Sheets.

## ⚙️ Automation Workflow

The workflow runs on a daily schedule and performs the following actions automatically:

1. Fetches NASA’s Astronomy Picture of the Day (APOD)
2. Downloads the space image
3. Retrieves subscriber emails from Google Sheets
4. Sends the NASA space photo to all subscribers via email

## ✉️ User Experience

After subscribing on the website, users will start receiving daily NASA space images directly in their email inbox.

## 🛠️ Tools Used

* n8n (Workflow Automation)
* NASA Open APIs
* Google Sheets
* Gmail
* Lovable.dev (Webpage)

## 👤 Author

Akash Jadhav
