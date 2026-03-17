# JobNear

A community-driven job platform designed to connect businesses and job seekers through location-based opportunities.

## Overview

**JobNear** is a system built to improve employment accessibility and streamline the hiring process within a community. By integrating map-based job discovery, it allows users to easily find nearby job opportunities and connect with local businesses.

The platform revolves around three main user roles—Admin, Job Poster, and Job Seeker—each playing a critical role in ensuring a secure, reliable, and efficient hiring ecosystem.

## User Roles & Features

### 👨‍💼 Job Poster

* 🏢 Post business details and job openings
* 📍 Set business location (displayed on map)
* 📝 Specify job requirements and descriptions
* 📥 Receive applications from job seekers
* ✅ Accept or ❌ reject applicants

Job posters can showcase their hiring needs publicly, making it easier to reach potential candidates within their area.

---

### 👩‍💻 Job Seeker

* 🗺 Browse verified job opportunities via map (GMap integration)
* 📄 View detailed job descriptions and requirements
* 📤 Submit applications and resumes
* 🔍 Explore nearby businesses hiring in real time

Job seekers benefit from a location-based interface that simplifies job searching and increases visibility of nearby opportunities.

---

### 🛠 Admin

* 🔐 Verify all system users (Job Posters & Job Seekers)
* 🏢 Validate business legitimacy through required documents
* 🪪 Confirm identity of job seekers (valid ID & personal information)
* ✅ Approve or ❌ reject user registrations
* ⚙️ Manage system maintenance schedules
* 🔔 Notify users before and after maintenance periods

Admins ensure that the platform remains secure, trustworthy, and free from fraudulent activity. Only verified users are allowed full access to system features.

## Key Features

* 🗺 Map-based job discovery (real-time visualization of job locations)
* 🔐 Role-based access control and verification system
* 📢 Public visibility of verified job postings
* 📊 Streamlined hiring and application process
* 🔔 Maintenance notification system for all users

## Tech Stack

### Frontend

* C#

Used to build a structured and responsive desktop application interface.

### Backend

* MongoDB (NoSQL database)

Handles flexible data storage for users, job postings, and applications.

## Technologies & Tools

* GMap.NET (NuGet Package)

  * Used for map integration and displaying business/job locations

* Geoapify

  * Converts addresses into geographic coordinates (latitude & longitude) for accurate map placement

* MongoDB Compass

  * GUI tool for managing and visualizing the database

## How It Works

Job Posters create listings by providing business details, job requirements, and location data. These listings are then displayed on the map, making them visible to Job Seekers.

Job Seekers can browse the map, explore job details, and submit applications directly through the system.

Before gaining full access, both Job Posters and Job Seekers must be verified by the Admin. This ensures that businesses are legitimate and users are authentic. Once verified, users can fully interact with the platform.

The system also includes a maintenance feature that notifies users in advance about scheduled downtime and when services will resume.

## Purpose

This project was built to:

* Increase employment opportunities within the community
* Simplify the hiring and job-seeking process
* Promote local businesses and workforce connections
* Practice building a role-based system with map integration
* Explore geolocation technologies and NoSQL databases

## Future Improvements

* Add real-time chat between job seekers and employers
* Implement job recommendation system
* Add mobile version for wider accessibility
* Enhance UI/UX for better user experience
* Integrate notifications (email/SMS) for applications and updates


---

Connecting opportunities with people—**JobNear** brings jobs closer to you.
