# Integrate SSRS RDLC Report with ASP.NET

This project demonstrates how to integrate **SSRS RDLC (Report Definition Language Client-side)** reports into an **ASP.NET** (Web Forms or MVC) application. RDLC reports allow you to display and print structured reports like invoices, sales summaries, and dashboards directly from a web application without requiring a SQL Server Reporting Services (SSRS) server.

---

## 🔧 Technologies Used

- ASP.NET (.NET Framework or .NET Core)
- RDLC Reports (SSRS Client-side)
- ReportViewer Control
- Visual Studio

---

## 📌 Features

- Embed and display RDLC reports in a web page.
- Load reports with data from a database or in-memory collections.
- Pass parameters to reports dynamically.
- Export reports to PDF, Excel, Word.
- Print directly from the browser (via ReportViewer).

---

## 📁 Folder Structure for ASP.NET Core 8
/YourProjectName │ ├── /Reports/ # RDLC report files │ └── SampleReport.rdlc │ ├── /Models/ # Data models │ └── ReportDataModel.cs │ ├── /Controllers/ or /Pages/ # Depending on MVC/WebForms │ └── ReportController.cs │ ├── /Views/ or /WebFormsPages/ # UI layer │ └── ShowReport.aspx / ShowReport.cshtml │ └── Web.config / appsettings.json

## Screenshots
<img width="959" alt="image" src="https://github.com/user-attachments/assets/6bca877d-fb3c-44da-ae12-f8493f10e592" />

