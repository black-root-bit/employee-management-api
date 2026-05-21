# 👥 employee-management-api

> HR backend for employee lifecycle — onboarding, attendance, payroll, leave management, performance reviews.

[![Java](https://img.shields.io/badge/Java-17-ED8B00?style=flat-square&logo=openjdk)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2-6DB33F?style=flat-square&logo=springboot)](https://spring.io/projects/spring-boot)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql)](https://postgresql.org)

**Features:** Employee CRUD with department hierarchy · Attendance tracking (clock in/out) · Leave request & approval workflow · Payroll calculation with deductions · Performance review cycles · Document storage (contracts, IDs) · Report generation (PDF/Excel) · Email notifications for approvals

**Key Endpoints:**
```
POST  /api/v1/employees                        # Add employee
GET   /api/v1/employees/{id}                   # Employee profile
POST  /api/v1/attendance/clock-in              # Clock in
POST  /api/v1/attendance/clock-out             # Clock out
POST  /api/v1/leaves/request                   # Leave request
PUT   /api/v1/leaves/{id}/approve              # Approve [MANAGER]
GET   /api/v1/payroll/{month}                  # Monthly payroll [HR]
GET   /api/v1/employees/{id}/payslip/{month}   # Download payslip
```

**GitHub Topics:** `java` `spring-boot` `hrm` `employee-management` `payroll` `rest-api` `postgresql` `docker`
