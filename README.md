# MaktabAttendanceSystem
A cloud-based attendance management system built using AWS Lambda, API Gateway, DynamoDB, S3, Python, HTML, CSS and JavaScript.

# Maktab Attendance Management System

A cloud-based attendance management system built using HTML, CSS, JavaScript, Python and AWS services.

## Overview

Maktab Attendance Management System is a web-based application designed to simplify student management and attendance tracking for educational institutions.

The system provides separate dashboards for teachers and administrators.

Teachers can view students, mark attendance and add comments for late-arriving students.

Administrators can manage student records and monitor attendance information.

## Problem

Traditional attendance systems often rely on paper registers and manual record keeping.

This can result in:

- Time-consuming attendance processes
- Difficulty maintaining records
- Higher chances of manual errors
- Difficulty finding previous attendance information
- Excessive paperwork

## Solution

This project provides a centralized digital attendance management system.

Teachers can record attendance digitally while administrators can manage student information through an admin dashboard.

## Features

### Teacher

- Teacher login
- Class selection
- View students
- Mark attendance
- Record late arrivals
- Add comments
- Update attendance information

### Admin

- Admin login
- View student records
- Manage students
- Delete students
- View attendance information
- Manage the student database

## AWS Architecture

```text
User
 │
 ▼
Amazon S3
 │
 ▼
API Gateway
 │
 ▼
AWS Lambda
 │
 ▼
Amazon DynamoDB
