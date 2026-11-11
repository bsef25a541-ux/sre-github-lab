# sre-github-lab

\# Glam desk (salon management system)

\## Overview

Glam Desk is a centralized salon management platform for scheduling, staff allocation, inventory, and client management.

Intended Benefit in your own words: It replaces manual logs, reduces double-bookings, streamlines front-desk operations, maximizes bookings, eliminates delays, and elevates the client experience.

\## Scope

\- In scope: 24/7 Online Booking - client picks service, stylist, time slot.

\- In scope: Interactive Calendar - real-time staff, service, and chair assignment.

\-  In scope: Automated Reminders - SMS and email alerts.

\-  In scope: Point of Sale \& Billing - multi-payment, vouchers, digital invoices.

\-  In scope: Inventory Tracking - product usage and low-stock alerts.

\-  Out of scope: Product delivery \& courier logistics.

\-  Out of scope: Off-site beauty dispatch \& GPS tracking.

\-  Out of scope: Direct factory supply procurement.

\## Stakeholders

\- Salon Client: Books services, pays, gets reminders, checks transparent pricing and preferred stylist.

\- Front Desk / Receptionist: Uses calendar, check-in, visit history, simple billing.

\- Stylist: Needs to know daily schedule, service duration, and commissions.

\- Owner / Manager : Needs to know revenue analytics, occupancy rates, staff performance, and real-time inventory. Needs to know which bookings are pending, which staff is free, and whether     salon is on track.

\- Project maintainer - System Administrator: Needs to manage security, high availability, role-based access, permissions, updates, database, and smooth performance. Needs to manage Stripe payments and Twilio / SendGrid messaging configuration.

\## Functional requirements

\- FR-01: The system shall let a client create a booking with service, stylist, and time slot.

\- FR-02: The system shall display the salon's saved bookings in a real-time calendar.

\- FR-03: The system shall let the system send reminders and let a client / staff mark a booking complete / cancelled.

\- FR-04: The system shall process billing with multi-payment, vouchers, and digital invoices.FR-05: The system shall track inventory and show low-stock alerts.

\## Nonfunctional requirements

\- NFR-01: With 100 saved bookings, the booking list / calendar shall appear within 2 seconds in at least 95 of 100 trials on an agreed test device. Online booking shall complete within 45 seconds.

\- NFR-02: Every booking action - create, view, cancel, mark complete - shall give visible feedback within 1 second, e.g. booking appears, confirmation shows, or tick shows.

\- NFR-03: The system shall work on desktop browsers, front-desk tablets, and mobile client app as Cloud SaaS, without double-booking.NFR-04: No-show rate shall reduce by 45% via reminders, front-desk phone time shall reduce by 50% within 3 months, and inventory accuracy shall be 95%+.

\## Acceptance criteria

\- FR-01: Measurable targets for operational excellence.

\- FR-02:45% No-Show Reduction - Fewer missed appointments via reminders.

\- FR-03:45s Booking Speed - Online booking in under 45 seconds.

\- FR-04:50% Front-Desk Savings - Less phone query time within three months.

\## Assumptions and open questions

\- Assumption A-01: The salon will have stable internet, and clients and staff will have smartphones with internet access.

\- Question Q-01:  From booking your last visit to leaving the salon, what was the most difficult part for you?

\- Question Q-02: When a client misses an appointment or comes late, what do you do at that time?

\## Project status and viewing

This is a documentation-only project. No application has been built.

\## Author

**Noshy (bsef25a541)**

\## Contributing

This is a documentation-only project. No application has been built.



