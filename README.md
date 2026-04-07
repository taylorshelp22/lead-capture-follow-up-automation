# Automated Lead Capture and Follow-Up System

## Overview

This project is an automated workflow designed to capture new leads, organize them, and ensure immediate follow-up communication.

It helps reduce response time for new inquiries while maintaining clean, structured lead data for ongoing use.

This system simulates a real-world lead intake process where speed and organization directly impact conversion rates.

---

## Problem

Many businesses collect leads but fail to respond quickly or consistently. This delay can result in lost opportunities and poor customer experience.

Additionally, lead data is often overwritten or disorganized, making it difficult to track and follow up effectively.

---

## Solution

This system automates the entire lead handling process:

1. Collect lead information through a Google Form  
2. Store raw lead data in a Google Sheets tab (unchanged)  
3. Monitor new submissions using Make  
4. Copy new leads into a “processed leads” tab for tracking  
5. Send confirmation email to the lead  
6. Send notification email to the realtor with lead details  

---

## Tools Used

- Google Forms (lead capture)
- Google Sheets (data storage and tracking)
- Make (automation workflow)
- Gmail (email notifications)

---

## Workflow Breakdown

1. Lead submits information through Google Form  
2. Data is stored in a raw data tab in Google Sheets  
3. Make detects a new row submission  
4. Lead data is copied to a processed leads tab  
5. Confirmation email is sent to the lead  
6. Notification email is sent to the realtor including:
   - Contact information  
   - Lead intent (buy, sell, explore)  

---

## Outcome

- Reduces response time to new leads  
- Prevents loss of potential clients  
- Maintains original raw data for accuracy  
- Creates a clear system for tracking processed leads  
- Improves organization and follow-up consistency  

---

## Future Improvements

- Add CRM integration  
- Add lead scoring or prioritization  
- Integrate SMS notifications  
- Track response and conversion rates  

---

## Project Status

Completed as a functional automation system with real-world application.
