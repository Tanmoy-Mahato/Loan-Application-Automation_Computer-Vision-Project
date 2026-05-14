# UiBank Loan Application Automation - Computer Vision Project

## Overview
This project automates the UiBank Loan Application process using UiPath Robotic Process Automation (RPA) with Computer Vision (CV) activities.

The automation performs:
- Login to UiBank website
- Navigation through loan application pages
- Loan application form filling
- Loan submission
- Loan approval/rejection verification
- Highlighting approval status using Computer Vision activities

The project demonstrates end-to-end UI automation using UiPath CV activities.

---

## Workflow Structure

### 1. UiBank_Login.xaml
Handles:
- Website launch
- Credential retrieval
- Username/password entry
- Login functionality

### 2. UiBank_Welcome1.xaml
Handles:
- First welcome page navigation
- Clicking Apply For A Loan button

### 3. UiBank_Welcome2.xaml
Handles:
- Second welcome page navigation
- Clicking second Apply For A Loan button

### 4. UiBank_ApplicationForm.xaml
Handles:
- Loan application form filling
- Dropdown selection
- Form submission

### 5. UiBank_LoanApprovedOrNot.xaml
Handles:
- Loan approval/rejection verification
- Highlighting result using CV Highlight activity

---

## Applications Used

| Application | Purpose |
|---|---|
| UiBank Website | Loan Application Processing |
| UiPath Studio | Automation Development |
| Windows Credential Manager | Secure Credential Storage |

---

## Author

**Tanmoy Mahato**

- UiPath RPA Developer
- Automation Enthusiast
- Computer Vision Automation Project

---
