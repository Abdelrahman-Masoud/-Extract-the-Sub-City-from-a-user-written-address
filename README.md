# -Extract-the-Sub-City-from-a-user-written-address

## 📝 Project Overview
This project solves a **data structuring challenge** where **25,000 Arabic student addresses** were written in unstructured formats.  
The goal was to **extract the sub-city** from each address to group students into **classes of 35** based on their location.

## 🚀 Solution Approach
To automate the extraction process, I used:
- **Google Cloud Geocoding API** for address processing
- **Python & Pandas** for data handling
- **Excel** for input and output

The script reads an Excel file with raw addresses, queries the **Google Geocoding API**, extracts the **sub-city (sublocality)**, and saves the structured data in a new file.

## 🔧 How to Use  
### 1 Install Required Libraries  
Run this command in your terminal:  
```bash
pip install requests pandas openpyxl

### 2 Install Required Libraries
Put your own API key in the code  
