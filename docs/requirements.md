# Requirements

## Functional requirements (what the system must DO)

1. **FR1 — User registration and login:** The system shall allow users to register and log in using their email addresses and passwords.
2. **FR2 — Preliminary sleep screening:** The system shall allow authenticated users to complete and submit the Pittsburgh Sleep Quality Index (PSQI) and Insomnia Severity Index (ISI) questionnaires.
3. **FR3 — Questionnaire scoring:** The system shall calculate PSQI and ISI scores according to their applicable scoring requirements and display the results separately as preliminary self-assessment information, not as a medical diagnosis.
4. **FR4 — Daily sleep diary:** The system shall allow authenticated users to record, save, and view personal sleep diary entries containing the date, bedtime, time taken to fall asleep, nighttime awakenings, wake-up time, and perceived sleep quality.
5. **FR5 — General sleep tips:** The system shall display prewritten sleep tips based on reliable health resources for general sleep health education.

## Non-functional requirements (how the system must PERFORM)

1. **NFR1 — Performance:** The system shall display the PSQI and ISI scoring results within 2 seconds after questionnaire submission under normal operating conditions.
2. **NFR2 — Security and privacy:** The system shall restrict access to personal screening results and sleep diary records to the authenticated user who owns those records and shall handle passwords securely.
3. **NFR3 — Usability:** At least 80% of participants in usability testing shall be able to complete the core tasks of logging in, submitting a screening questionnaire, and saving a sleep diary entry without assistance.