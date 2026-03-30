# FarmEase

FarmEase is a comprehensive farm management system designed to streamline agricultural operations. This repository contains the source code for both the administrative web dashboard and the cross-platform mobile application.

## Architecture & Tech Stack
This solution is built using a modern C# and .NET ecosystem, leveraging the following technologies:
* **Web Backend/Admin Portal:** .NET Blazor Server utilizing the DevExpress eXpressApp Framework (XAF).
* **Mobile Application:** .NET MAUI for cross-platform deployment across iOS, Android, MacCatalyst, and Windows.
* **Data & Business Logic:** Shared modules handling business objects, authentication, and localization.

## Key Features
* **Crop Management:** Track crop types, resources, and specific land assignments.
* **Crop Cycle Tracking:** Manage and monitor the complete lifecycle of crops from planting to harvest using dedicated tracking modules.
* **Task & Schedule Management:** Integrated To-do lists, scheduling tools, and task progress tracking for farm operations.
* **Analytics & Reporting:** Built-in charting features and report generation for yield and resource analysis.
* **Cross-Platform Accessibility:** Manage operations seamlessly from the web dashboard or on the go using the MAUI mobile app.

## Project Structure
* `FarmEase_230508.Blazor.Server/` - The Blazor Server web application, UI controllers, and custom DevExpress configurations.
* `FarmEase_230508.Maui/` - The .NET MAUI mobile application featuring custom themes, charts, and push notification integrations.
* `FarmEase_230508.Module/` - The core application module containing shared business objects (e.g., `Crop`, `CropCycle`, `Farm`, `Land`) and database update scripts.
* `FarmEase_230508.E2E.Tests/` - End-to-end testing suite.
* `MauiThemes/` & `MauiStocksMini/` - Supplementary MAUI styling and charting components.

## Getting Started

### Prerequisites
* .NET 7.0 or higher SDK
* Visual Studio, Google Antigravity IDE, VS Code, or IntelliJ configured for .NET development.
* Required DevExpress NuGet packages configured in your environment.

### Running the Application
1. Clone the repository.
2. Restore the NuGet packages for the solution (`FarmEase_230508.sln`).
3. Set `FarmEase_230508.Blazor.Server` as the startup project to launch the web administration portal.
4. Set `FarmEase_230508.Maui` as the startup project and select your target emulator/device to run the mobile application.

## Author

**Renee Llup** Senior Full-Stack Software Engineer & IT Consultant
