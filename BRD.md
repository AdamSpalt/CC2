# Business Requirements Document (BRD)
## Project: Contract Compas v2

### 1. Document Overview
* **Project Name:** Contract Compas v2
* **Objective:** A web application to manage and track personal insurance contracts and subscriptions.
* **Author:** Adam Spaltenstein
* **Status:** Draft

---

### 2. Executive Summary
Contract Compas v2 is a modern web application designed to help individuals centralize, manage, and track all their personal insurance policies and subscriptions (e.g., auto, home, health life insurance, streaming services, gym memberships). The system will provide clear visualization of costs, alert users before auto-renewals or cancellation deadlines, and serve as a secure digital vault for contract documents.

---

### 3. Target Audience
* Individuals looking to optimize their monthly/annual expenses.
* Users who want to avoid accidental subscription auto-renewals.
* Families needing a centralized place to store insurance policies and contact details for providers.

---

### 4. Key Functional Requirements

#### 4.1. Dashboard & Analytics
* **Total Spend Overview:** Visual breakdown of monthly and annual expenditures.
* **Category Breakdown:** Graphical chart (e.g., pie chart or progress bars) showing spend by category (Insurance, Utilities, Entertainment, etc.).
* **Upcoming Events Timeline:** A list or calendar view highlighting upcoming renewal dates and cancellation notice deadlines.

#### 4.2. Contract & Subscription Management
* **Add/Edit/Delete Contracts:** Form to input contract details:
  * Provider Name (e.g., Allianz, Netflix)
  * Contract Type / Category (e.g., Insurance, Subscription, Utility)
  * Cost (Amount & Billing Cycle: Monthly, Quarterly, Yearly)
  * Start Date & End Date
  * Notice Period (e.g., 1 month, 3 months before end date)
  * Status (Active, Paused, Terminated)
  * Document Attachment (PDF or image upload placeholder)
  * Custom Notes (e.g., policy number, support phone number)
* **Search & Filter:** Find contracts easily by provider name, category, or status.

#### 4.3. Alerts & Notice Tracking
* **Notice Period Indicator:** Automatic calculation of the last date to cancel the contract to avoid auto-renewal.
* **Status Badges:** Color-coded status labels (e.g., "Active" in green, "Notice Period Active" in amber, "Action Required" in red).

---

### 5. Non-Functional & UI/UX Requirements
* **Modern Premium Design:** Clean, elegant dark/light theme options with smooth transitions, curated harmonious colors, and clean typography.
* **Fully Responsive:** Optimised for desktop, tablet, and mobile browsers.
* **Local Storage / Offline Capability:** Support storing data locally for ease of use and privacy first.

---

### 6. Technical Stack (Proposed)
* **Frontend:** HTML5, Vanilla CSS (Premium styling with animations), Vanilla JavaScript.
* **Data Storage:** LocalStorage/IndexedDB for client-side storage, with options to export/import JSON data for backups.
