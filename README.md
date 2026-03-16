# CADTPS Malaria Diagnosis and Treatment Planning System

This project presents the design of a Computer-Aided Diagnosis and Treatment Planning System (CADTPS) for malaria.

The system was conceived to support healthcare professionals in the accurate and timely diagnosis of malaria while also assisting with treatment planning. It is especially relevant in low-resource settings where access to experienced specialists and advanced diagnostic infrastructure may be limited.

## Project Background

Malaria remains a major public health challenge, particularly in resource-constrained environments. Accurate diagnosis and effective treatment planning can be difficult and time-consuming, leading to delayed treatment, misdiagnosis, and poor patient outcomes.

CADTPS was designed as a digital clinical support system that helps structure patient data, analyze symptoms and test information, guide diagnosis, and support treatment decisions.

## Aim

To develop a computer-aided diagnosis and treatment planning system that assists healthcare professionals in the accurate and timely diagnosis of malaria and supports effective treatment planning.

## Objectives

- Design a user-friendly system for entering patient and diagnostic data
- Support diagnosis using structured patient symptoms and laboratory results
- Assist treatment planning using patient-specific clinical factors
- Improve healthcare decision-making in low-resource settings
- Provide reminders, alerts, and follow-up support for patient care

## Key Features

- Role-based access for Admin, Doctor, and Patient
- Patient registration and medical record management
- Symptom and test result entry
- Automated diagnosis support
- Malaria type prediction support
- Severity classification
- Treatment plan assignment
- Dosage and schedule support
- Medication reminders
- Follow-up alerts
- Acute case notifications
- Analytics dashboard
- Secure data handling

## User Roles

### Admin
- Login
- Add or remove doctors
- View patient records
- Access analytics dashboard

### Doctor
- Login
- Add, view, and update patients
- Input symptoms and test results
- Get automated diagnosis support
- Assign treatment plans
- Set reminders
- Receive acute case alerts

### Patient
- Login or access via doctor
- View diagnosis and treatment plan
- Receive medication reminders
- Receive appointment or follow-up alerts

## Diagnosis and Treatment Logic

The proposed system supports:
- prediction of malaria type
- classification of severity as mild, moderate, or severe
- treatment planning based on age, drug allergies, history, and related risk factors
- medication schedules and dose guidance
- drug safety and contraindication checks

## Repository Structure

- `app_design/` – UI/UX flow, role-based screens, and app design notes
- `diagnosis_logic/` – diagnosis workflow and prediction concept notes
- `treatment_planning/` – treatment support logic and reminder workflow
- `system_diagrams/` – architecture diagrams, user flow, and system models
- `images/` – screenshots, mockups, and visual materials
- `documentation/` – write-up, feature draft, and supporting notes

## Relevance

This project demonstrates how intelligent digital systems can support healthcare workers by combining structured data entry, diagnostic guidance, treatment support, and patient follow-up within a unified application workflow.

## Author

John Afriyie Oduro
