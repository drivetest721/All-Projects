# RPA - Automated Bill Processing Solution

## Overview
**Robotic Process Automation (RPA)** enhances efficiency and accuracy by automating **repetitive** and **time-consuming** business processes. This project focuses on automating the **bill downloading and posting process**, reducing manual effort, minimizing errors, and optimizing workflow execution.

### **Client Challenge**
The client requires **posting 700+ invoices per month**, involving:
- Visiting **~10 vendor websites** manually
- Locating the **latest bills** and downloading them
- Extracting relevant data for posting
- Submitting data manually on a separate **bill posting platform**

This **manual** approach led to inefficiencies, delays, and potential errors.

## **Solution: End-to-End Automation**
To overcome these challenges, we implemented a **two-phase automation strategy** using **UiPath, Playwright, and AI-driven Data Extraction**.

### **Project 1: Bill Downloading Automation**
✅ **Automates the retrieval of bills from ~10 vendor websites**
✅ Uses **UiPath bots** to log in, navigate vendor portals, and download bills
✅ Ensures **consistent, error-free** bill collection

### **Project 2: Bill Posting Automation**
✅ **Automates bill posting from ~80 vendors**
✅ Uses **AI-based data extraction** to parse PDF invoices
✅ Generates **structured JSON files** for data population
✅ Uses **UiPath to automate submission**, eliminating manual errors

## **Technology Stack**
- **Primary Automation Tool:** UiPath
- **AI for Data Extraction:** Python (OCR, NLP, Pandas)
- **Web Automation:** Playwright (for bill downloads)
- **Target Platform:** Online Bill Posting Website
- **Secure Credentials Management** for vendor logins

## **How the Automation Works**
1. **Bill Retrieval:**
   - Playwright navigates vendor portals and downloads invoices.
   - PDFs are stored for processing.
   
2. **Login & Secure Access:**
   - UiPath automates login authentication using **encrypted credentials**.
   
3. **AI-Based Data Extraction:**
   - Python extracts key invoice details (vendor name, amount, date, etc.).
   - Data is structured into a **JSON file**.
   
4. **Automated Bill Posting:**
   - UiPath reads JSON data and fills web forms automatically.
   - The form is **submitted with error handling**.
   
5. **Final Submission & Reporting:**
   - UiPath ensures successful submission.
   - The system handles **errors, retries, and logs activity**.

## **Impact & Results**
🚀 **Faster Processing:** 700+ invoices processed seamlessly per 

📉 **Reduced Errors:** Eliminates manual data entry mistakes


💰 **Cost Savings:** ~58 hours of manual work saved per month

⚡ **Scalability:** Supports increased invoice volume without additional resources

😃 **Improved Customer Satisfaction:** Faster, error-free billing

## **Key Benefits of RPA Automation**
✅ **Faster Billing Processes:** Automated workflows reduce delays

✅ **Eliminates Manual Effort:** No human intervention required for posting

✅ **Error Reduction:** AI-driven validation ensures accuracy

✅ **Scalable Solution:** Easily handles growing invoice volumes

✅ **Cost-Effective:** Significant savings on operational expenses
