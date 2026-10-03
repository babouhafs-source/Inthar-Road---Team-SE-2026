# Inthar Road - Team SE-2026

## Project Name
Inthar Road - Road Accident Detection and Alert System

## Team Members
- ALLALI Sidali Abderaoufe
- BELANIGUE Dhiaa Eddine Islam 
- BOUABDALLAH Abderrahmane 
- BOUHAFS Abdennour 
- ATTOUI Amine 

## Type of Software
Artificial Intelligence / Computer Vision / Web Application

## Brief Description
Inthar Road is an intelligent road accident detection system designed to detect possible traffic accidents from camera or video footage. When an accident is detected, the system generates an alert containing information such as the detection time, location, confidence, and video evidence. The system is designed to assist emergency services such as Civil Protection in monitoring and responding to road accidents.

## Implementation Stage

The system was implemented using **Python**, **YOLOv8n**,and **OpenCV** for vehicle detection and video processing. A custom tracking and accident-analysis system was developed using vehicle trajectories, bounding-box overlap (IoU), distance, relative velocity, and temporal consistency to distinguish possible accidents from normal traffic situations and reduce false detections.

The backend was developed with **FastAPI** and **SQLite** to manage accident records, uploaded videos, and system data. **WebSockets** were implemented to send accident alerts to the monitoring dashboard in real time, while the system maintains a 7-second frame buffer to save video evidence before an accident is detected.

A web-based dashboard was also implemented to display the processed video stream, accident alerts, accident information, and stored accident records. The system supports both uploaded video files and external camera/stream URLs for accident detection.
