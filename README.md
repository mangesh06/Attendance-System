# README: Computer Vision System for Tracking Attendance

## Overview
This project presents a computer vision (CV) system designed for automating attendance tracking using facial recognition technology. The primary aim is to replace manual and inconsistent attendance methods with an accurate, real-time system, enhancing efficiency and reliability.

## Agenda
1. Introduction
2. Overall End-to-End Solution
3. CV Model
4. Addressing Potential Challenges
5. Conclusion and Next Steps
6. Task Contribution and Owner
7. References

## Introduction
### Problem Overview and Current Situation
- **Current Issues**: Attendance tracking at ASU MSBA courses is manual, leading to inaccuracies and inefficiencies.
- **Impact**: These inefficiencies compromise the integrity of the grading system, affect faculty workload, and may unfairly impact student evaluations.
- **Solution**: Implement a CV-based attendance system to automate the process, ensuring accurate and efficient attendance recording.

### Ensuring Privacy & Security
- **Data Handling**: Implement strict data handling protocols, including data encryption, limited access protocols, and continuous monitoring.
- **Compliance**: Ensure all processes comply with privacy laws and ASU’s privacy policies.

### Stakeholders and Beneficiaries
- **Faculty**: Streamlined processes and reduced administrative burden.
- **Admin Staff**: More accurate and fair evaluation of student attendance.
- **Students**: Fair and transparent recording of attendance, enhancing engagement.

## Overall End-to-End Solution
### Steps Involved
1. **Orientation Photography**: Capture official pictures of students during mandatory orientation.
2. **Cohort Cataloging**: Record and sort student pictures in the MSBA database.
3. **Camera Setup**: Install and calibrate cameras in each classroom.
4. **Application Activation**: Instructors activate the attendance application at the start of each session.
5. **Facial Recognition**: The system detects student faces and matches them with the cohort.
6. **Attendance Logging**: Record student ID numbers and timestamps in the attendance spreadsheet.
7. **Attendance Reporting**: Instructors can manually email the attendance spreadsheet to the designated recorder.

## CV Model
### Why CV?
- **Efficiency**: Enables real-time, scalable attendance tracking without additional hardware.
- **Accuracy**: Vital for precise face detection and recognition, reducing errors associated with manual tracking.

### Model Overview
- **Library**: Based on the `face_recognition` library.
- **Deep Learning**: Utilizes pre-trained models from dlib for feature encoding and comparison.
- **Validation**: External validation conducted on separate datasets, with ongoing monitoring and updates.

### Methodology
- **Training Data**: Pre-trained on a large dataset of human faces, with diverse images to improve generalization.
- **Evaluation Metrics**: Accuracy, precision, recall, and F1-score.
- **Bias Mitigation**: Ensure representation of different demographics to mitigate bias.

### Challenges and Mitigation
- **Privacy and Consent**: Ensure transparency, obtain consent, use strong encryption, and implement strict access controls.
- **Accuracy and Bias**: Use diverse training datasets, update algorithms regularly, and conduct frequent accuracy checks.
- **Technical Issues**: Invest in quality hardware, ensure regular maintenance, and establish manual overrides or backups.
- **System Integration**: Design for compatibility and use middleware or APIs for smooth data exchange.

## Conclusion & Findings
- **Efficiency Gains**: Ensures real-time, accurate attendance data.
- **Standardization**: Provides a standardized system for managing class participation.
- **Cost-Effectiveness**: Presents a practical solution for educational institutions.
- **Positive Impact**: Enhances the learning environment, leading to student empowerment and accountability.

### Next Steps
- **Expansion**: Consider expanding the use of the CV-based attendance system to other programs within the university.
- **Continuous Improvement**: Enhance the system based on user feedback, refine algorithms, and improve integration.
- **Compliance & Regulations**: Stay updated on privacy regulations, conduct regular assessments, and maintain transparency.
- **Research & Development**: Explore emerging technologies such as biometric authentication, blockchain for secure data management, and IoT devices for automated tracking.

## References
- Various online resources discussing facial recognition technology and its application in attendance systems.