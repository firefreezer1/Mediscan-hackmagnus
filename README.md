# Mediscan

Mediscan is a healthcare prototype designed to enable early medical consultation by allowing patients to record vital signs using a hardware device and transmit the data digitally to hospitals and doctors for quick review and action.

The system provides separate interfaces for patients, hospital administrators, and doctors to ensure proper routing, filtering, and medical response.

---

## 🚀 Features

- Patient can submit vital health data remotely  
- Hospital admin panel to review and route incoming requests  
- Doctor dashboard to view patient reports  
- Chat and video call support for immediate consultation  
- Digital storage of patient health records  
- Reduces delay in medical attention  

---

## 🏗 System Overview

The Mediscan system consists of three main components:

1. Patient Interface – Used to upload vitals and symptoms  
2. Hospital Admin Panel – Filters spam and assigns cases to doctors  
3. Doctor Dashboard – Displays reports and enables consultation  

Data flow:  
Patient → Hospital Admin → Doctor → Patient (via chat/video call)

---

## 🛠 Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Backend: Node.js / Firebase / Flask (based on implementation)  
- Database: MongoDB / Firebase / MySQL  
- Hardware (prototype): ESP32 with MAX series sensors (e.g., MAX30102)  
- Communication: WiFi-based data transfer  

---

## ⚙️ Installation & Setup

1. Clone or download the repository:

2. Navigate into the project folder:

3. Install required dependencies:


4. Start the server:

or


5. Open the frontend in your browser.

---

## ▶️ Usage

1. Patient records vitals using the hardware device.  
2. Data is uploaded through the patient interface.  
3. Hospital admin reviews the request and assigns it to a doctor.  
4. Doctor views the report on the dashboard.  
5. Doctor can initiate chat or video call for immediate guidance.

---

## 🎥 Demo

A prototype demo video is included showing:
- Patient data submission  
- Admin routing process  
- Doctor report viewing  
- Live consultation flow  

---

## 🌍 Real-World Problem Addressed

Mediscan addresses delayed medical attention and fragmented health records by enabling remote transmission of vital health data and faster access to medical consultation without requiring immediate physical hospital visits.

---
oject is a prototype developed for hackathon and academic purposes.
