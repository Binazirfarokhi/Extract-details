# Extract-details from PDF 

## Document Processing with Power Automate & AI Builder

This project demonstrates how to use **Power Automate** and **AI Builder** to automatically extract key information from PDF documents and make it available for different business scenarios (validation, reporting, or storing in data sources).

### Project Overview

Many organizations still receive important information as PDF files (forms, registrations, orders, etc.). Manually reading and copying this data is slow and error-prone.

In this solution, I:

- Built a **Document Processing model** with **AI Builder**
- Trained the model with **multiple PDF formats and layouts** to increase accuracy
- Created a **Power Automate flow** that:
  - Takes PDF files from **SharePoint** / **OneDrive** (attachments)
  - Sends the file to the AI Builder model
  - Extracts key fields such as **Name**, **Family Name**, **Order Number**, and **Address**
- Connected the model to a **Canvas Power App** so users can upload a PDF and see the extracted details instantly

This automation helps businesses process documents faster and reduces manual data entry.

### Key Features

- ✅ Uses **AI Builder – Document Processing** (fixed template model)  
- ✅ Trained with **different PDF styles and shapes** to handle real-world variations  
- ✅ **Power Automate flow** to orchestrate the process end-to-end  
- ✅ Supports files coming from **SharePoint libraries**, **OneDrive**, or **uploaded from a Canvas App**  
- ✅ Using Canvas App to run the flow and extract the info.




### Technologies Used

- **Power Apps (Canvas App)**
- **Power Automate**
- **AI Builder – Document Processing**
- **SharePoint / OneDrive** for file storage

