# MedSync Health Records 🏥

**A multi-clinic patient medical-history dashboard prototype**

MedSync is a web-based prototype designed to demonstrate how patient medical histories from multiple healthcare facilities could be organized into one accessible timeline. It presents patient summaries, clinic visits, complaints, diagnoses, and prescription information in a centralized interface.

> **Project status:** Frontend prototype using hardcoded demonstration data. A production database, backend API, authentication, and healthcare-grade security are not implemented in the current version.

## ✨ Features

- **Patient selection:** Choose a demonstration patient from the sidebar.
- **Patient summary:** Display blood group, clinic count, and total visits.
- **Medical-history timeline:** View visits with dates, clinics, cities, doctors, and specialties.
- **Clinical details:** Organize chief complaints, diagnoses, and prescription information.
- **Responsive content layout:** Use a structured dashboard with a scrollable history area.
- **Loading and empty states:** Demonstrate selection, loading, and record-display interactions.
- **Dark interface:** Use a consistent visual design with distinct diagnosis and prescription labels.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Layout, styling, animations, and theme |
| JavaScript | Patient selection, mock data, and dynamic rendering |
| Font Awesome | Interface icons |
| Google Fonts (Inter) | Typography |

## 🧩 How It Works

1. The user selects a demonstration patient.
2. JavaScript retrieves the corresponding entry from the local `mockDatabase` object.
3. The dashboard updates the patient summary.
4. Medical visits are rendered as timeline cards.
5. The user can select another patient to view a different demonstration history.

### Architecture

```text
Patient Selection
       ↓
JavaScript Event Handler
       ↓
Local Mock Database
       ↓
Patient Summary + Visit Timeline
```

## 🚀 Run Locally

1. Clone or download this repository.
2. Open the project folder.
3. Open `index.html` in a modern web browser.

No build step or package installation is required for this standalone HTML prototype. An internet connection is needed for the externally hosted Google Fonts and Font Awesome assets.

## 📁 Repository Structure

```text
medsync-health-records/
├── index.html
├── README.md
└── Multi-Clinic Patient Medical History Tracking System.pptx
```

## 🔒 Privacy and Data Limitations

This version uses hardcoded demonstration records. It is not designed to store or share real patient information and should not be used for actual clinical decisions.

Before handling real medical records, the system would need appropriate authentication, role-based authorization, secure storage and transmission, audit logging, input validation, consent and access controls, and a suitable privacy and compliance review.

## 🔭 Planned Improvements

- Connect a backend API and a relational database such as MySQL.
- Implement patient and healthcare-professional authentication with role-based permissions.
- Add patient search, record filtering, and record-entry validation.
- Add automated functional tests and error handling.
- Add analytics for visit counts, clinic distribution, and visit trends.
- Improve accessibility and responsive behaviour on mobile screens.
- Document the architecture, setup, tests, and known limitations.

## 📊 Evaluation

The current project is a user-interface and data-organization prototype. No machine-learning model or clinical prediction system is implemented, so classification metrics such as accuracy, precision, recall, ROC-AUC, and a confusion matrix are not applicable to this version.

Future evaluation can include functional-test pass rates, response times after backend integration, and data-integrity checks.

## 👩‍💻 Author

**Mithravinda U**

GitHub: [@MithravindaU](https://github.com/MithravindaU)

---

*Built as a prototype exploring how a unified patient-history interface could support continuity of care across healthcare facilities.*
