# Performance Testing Using Apache JMeter

## 📌 Introduction
This repository contains performance testing artifacts created using **Apache JMeter** for the **Restful-Booker API**, a public sample API used for load and stress testing.

The testing includes simulation of concurrent users to measure **response time, throughput, and system behavior** under varying loads.

This project can be used as a reference for learning **API performance testing using JMeter**.

**URL:**  
https://restful-booker.herokuapp.com/booking  

---

## 🧪 Test Case Scenarios  
**Restful-Booker API**

The test plan includes the following scenarios:

- **Create Booking** — Simulate users creating bookings  
- **Get Booking** — Fetch booking details  
- **Update Booking** — Modify existing booking data  
- **Delete Booking** — Remove booking records  

The goal is to evaluate API performance under increasing numbers of virtual users and identify response times and error rates.

---

## ▶ How to Run

1. Clone this project  
2. Open `booking.jmx` file in **JMeter**  
3. Create the API collection in **Postman** (for reference)  
4. Set up the required configurations in **JMeter**  
5. Run the test plan  
6. Check the **Summary Report** and **HTML Report** for output  

---

## 🛠 Technology Used

- **Apache JMeter** — Performance and load testing tool  
- **Java JDK** — Required to run JMeter  
- **Restful-Booker API** — Target API under test  
- **Excel / HTML Reports** — Used for performance analysis  

---

## 📁 Project Files

| File                           | Description                   |
| ------------------------------ | ----------------------------- |
| `booking.jmx`                  | JMeter test plan              |
| `bookingLoadTest.jtl`          | Load test result data         |
| `bookingStressTest.jtl`        | Stress test result data       |
| `booking-api-test-report.xlsx` | Performance analysis in Excel |
