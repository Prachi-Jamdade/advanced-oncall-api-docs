# Zenduty Advanced On-Call Scheduling with Timezone Intelligence

## Overview

Zenduty now supports advanced on-call scheduling with timezone intelligence. This feature makes it easier for teams working in different parts of the world to manage shifts and escalations fairly and efficiently.

---

## What’s New

- **Timezone-Aware Scheduling** — Each participant can be assigned a timezone and working hours.
- **Custom Rotations** — Support for daily, weekly, and custom rotation patterns.
- **Holiday Calendars** — Add national or regional holiday calendars to skip rotations on holidays.
- **Fallback User Support** — Automatically assign a fallback user when no one is available.

---

## Available API Endpoints

You can interact with these features through the following endpoints:

1. **Create Schedule**  
   `POST /api/v2/schedules`  
   Create a new schedule with timezone-aware participants.

   ![Create Schedule](./assets/create-schedule.png)

3. **List Schedules**  
   `GET /api/v2/schedules`  
   Get all existing schedules.

   ![List Schedules](./assets/list-schedules.png)

5. **Get Schedule by ID**  
   `GET /api/v2/schedules/{schedule_id}`  
   Retrieve details of a specific schedule.

   ![Get Schedule By ID](./assets/get-schedule-by-id.png)

7. **Update Schedule**  
   `PUT /api/v2/schedules/{schedule_id}`  
   Modify an existing schedule.

   ![Update Schedule](./assets/update-schedule.png)

9. **Delete Schedule**  
   `DELETE /api/v2/schedules/{schedule_id}`  
   Remove a schedule.

   ![Delete Schedule](./assets/delete-schedule.png)

You can import our Postman collection to start testing all endpoints. Each request comes with pre-filled example data and supports easy authentication setup.

[Download Postman Collection](Zenduty-Advanced-On-Call-Scheduling-API.postman_collection.json)

Need help? Join our [community](https://community.zenduty.com/) and let's chat!
