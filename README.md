# Conference Room Booking App

## Overview
The Conference Room Booking App for Webskitters Technology Solutions Pvt. Ltd. is a mobile application designed to facilitate seamless booking of conference rooms and meeting pods. The app ensures optimal resource utilization, supports recurring meetings, provides intelligent room recommendations, and allows admins to manage bookings effectively.

---

## Features

### User Roles

#### 1. Regular User:
- Book and manage conference rooms or meeting pods.
- View intelligent room suggestions based on attendee count.
- Receive notifications for cancellations, rescheduling, or room availability.
- End meetings to free up rooms for others.

#### 2. Admin:
- Add and manage users.
- View and manage all bookings.
- Override meeting requests for urgent requirements.

#### 3. Super Admin:
- Full access to all bookings and user management.
- Override and cancel existing bookings for urgent meetings.

---

## Functional Requirements

### chat prompt
- I can book a room using prompt 
- Super admin can create prompt 


### Room Booking
- **Conference Rooms:** Book up to 1 week in advance.
- **Meeting Pods:** Book up to 1 day in advance.
- Intelligent room suggestions based on attendee count.

### Recurring Meetings
- Users can set recurring bookings with defined intervals.

### Room Utilization Optimization
- System suggests optimal room allocation to prevent underutilization.

### Alternative Time Suggestions
- Suggest the next available slot in case of room unavailability.

### Meeting Management
- Organizers can:
  - Cancel, reschedule, or end meetings.
  - Notify users about changes.
- Super admins can override bookings for urgent meetings.

### Notifications
- Notifications for:
  - Room booking confirmation.
  - Meeting changes or cancellations.
  - Availability of previously requested rooms.

### Admin Panel
- Manage users and room bookings.
- Approve or reject room requests.
- Handle urgent meeting overrides.

---


## Conference Rooms and Capacities

### Conference Rooms:
1. Can create conference room with name and max capacity
2. Name must be unique


### Meeting Pods:
- Small meeting rooms with a capacity of 4 people.
- Super admin can create meeting pods with unique name

---

## Tech Stack
- **Frontend:** Next.js, Clerk
- **Backend:** tRPC, Prisma, Next Auth
- **State Management:** Zustand
- **Database:** sqllite

This is a [T3 Stack](https://create.t3.gg/) project bootstrapped with `create-t3-app`.

## What's next? How do I make an app with this?

We try to keep this project as simple as possible, so you can start with just the scaffolding we set up for you, and add additional things later when they become necessary.

If you are not familiar with the different technologies used in this project, please refer to the respective docs. If you still are in the wind, please join our [Discord](https://t3.gg/discord) and ask for help.

- [Next.js](https://nextjs.org)
- [NextAuth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [Drizzle](https://orm.drizzle.team)
- [Tailwind CSS](https://tailwindcss.com)
- [tRPC](https://trpc.io)

## Learn More

To learn more about the [T3 Stack](https://create.t3.gg/), take a look at the following resources:

- [Documentation](https://create.t3.gg/)
- [Learn the T3 Stack](https://create.t3.gg/en/faq#what-learning-resources-are-currently-available) — Check out these awesome tutorials

You can check out the [create-t3-app GitHub repository](https://github.com/t3-oss/create-t3-app) — your feedback and contributions are welcome!

## How do I deploy this?

Follow our deployment guides for [Vercel](https://create.t3.gg/en/deployment/vercel), [Netlify](https://create.t3.gg/en/deployment/netlify) and [Docker](https://create.t3.gg/en/deployment/docker) for more information.
