# EcoLife – Environment & Animal Safety Hub

A community-focused platform designed to support environmental awareness, animal welfare reporting, and incident tracking.

## Overview

EcoLife provides a centralized application where users can submit environmental concerns and animal safety reports, view reported incidents, and access educational resources.

The platform aims to improve community participation in environmental protection and responsible animal welfare.

## Key Features

- Submit environmental hazard reports
- Report animal safety and welfare concerns
- Record incident descriptions, locations, and dates
- Upload supporting images where supported
- Track report status
- Maintain incident records
- Browse environmental awareness resources
- Provide administrative report review
- Display incident statistics and summaries

## Technology Stack

- Python
- Flask
- MySQL
- HTML5 and CSS3
- Bootstrap
- JavaScript

## Proposed Database Tables

- `users`
- `environmental_reports`
- `animal_safety_reports`
- `incident_categories`
- `report_updates`
- `awareness_resources`

## Project Structure

```text
EcoLife-Environment-Animal-Safety-Hub/
├── app.py
├── config.py
├── database.sql
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
├── templates/
├── static/
├── uploads/
└── tests/
```

Uploaded files should be stored securely and excluded from Git when they contain private or sensitive information.

## Installation

```bash
git clone https://github.com/amoltathesoftwareengineer/EcoLife-Environment-Animal-Safety-Hub.git
cd EcoLife-Environment-Animal-Safety-Hub
python -m venv .venv
```

Activate the virtual environment on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure the database and environment variables before running the application.

## Run the Application

```bash
python app.py
```

Open the local development URL displayed in the terminal.

## Intended Users

- Community members
- Environmental awareness groups
- Animal welfare volunteers
- Report reviewers and administrators

## Responsible Use

The platform is intended for reporting and information management. It does not replace emergency services, veterinary care, or authorized environmental enforcement agencies.

Avoid publishing private addresses or personal information without permission.

## Future Enhancements

- Interactive incident map
- Email notifications
- Image-based report categorization
- Environmental statistics dashboard
- Multilingual interface
- Mobile-friendly reporting workflow

## Author

Amol Tathe

GitHub: https://github.com/amoltathesoftwareengineer

## License

Add an appropriate open-source license before permitting reuse.
