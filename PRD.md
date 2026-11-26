## 1. Background & Problem Statement

Students at Babcock University currently face significant daily friction when commuting across campus due to the lack of a dedicated, student-accessible transit system. At present, the primary mode of motorized campus transport consists of staff-operated auto-rickshaw tricycles, locally known as **Keke**.

While Kekes serve as the default transit option, relying on them creates several recurring pain points for the student body:

* **Uneven Geographic Coverage:** Keke drivers rarely circulate across the entire campus. Instead, they cluster around strategic, high-traffic hubs where passenger volume and quick turnarounds are guaranteed (e.g., **Ameyo Hall** and behind the **Cafeteria**). Students in quieter halls or distant academic blocks are frequently left stranded.
* **Poor Service & Unpredictability:** Students regularly experience dismissive behavior from drivers, including being ignored when flagging down rides or dealing with uncooperative attitudes.
* **Expensive Workarounds:** To bypass the unreliability of standard Keke queues, some students resort to paying specific drivers a retainer to act as "private drivers" on call—an informal workaround that is too costly for the average student.
* **Physical Toll & Heat Exhaustion:** Because of the cost, poor availability, and friction involved in getting a Keke, a large portion of the student body walks to class every day. Trekking long distances under the intense sun—worsened by extreme heat waves and **El Niño** weather conditions—leaves students exhausted before lectures even begin.

---

## 2. Product overview:

Introduce a **Campus Bicycle Booking & Rental System** designed specifically for Babcock University students. Rather than competing with Kekes on a stressful, per-minute basis, the platform allows students to **book and rent bicycles for extended periods (multiple days or full weeks)**.

### Business objectives
* **Guaranteed Personal Mobility:** Students have a dedicated bicycle at their disposal for the duration of their rental period, eliminating wait times at pickup hubs.
* **Cost-Effective Alternative:** Multi-day and weekly rental tiers offer an affordable middle ground between exhausting daily walks and expensive "private Keke" arrangements.
* **Campus-Wide Access:** Students can commute directly between hostels, lecture halls, the cafeteria, and sports facilities on their own schedule.
* **Weather & Time Efficiency:** Cuts down transit time under harsh sun and high temperatures, allowing students to arrive at classes faster and with less physical fatigue.


---

## 3. Target Users

* **Primary Users (Students):** Undergraduate and postgraduate students living on campus who need reliable, affordable, and flexible daily transportation between halls of residence and academic buildings.
* **System Administrators (Fleet & Ops Managers):** Campus staff or student operators responsible for bicycle maintenance, inventory tracking, hub management, and verifying student bookings.


**Safety & Liability Agreement**: As a first-time renter, I want to review and digitally sign the campus bicycle safety rules and liability terms, so that I understand approved riding routes, designated parking zones, and damage policies before riding.
## Success Metrics (KPIs)
**Student Adoption Rate**: Percentage of on-campus students creating verified accounts within the first semester (Target: 25% of the student body).

**Fleet Utilization Rate**: Percentage of active bicycles rented out on any given weekday during term time (Target: >75%).

**Repeat Booking Rate**: Percentage of first-time renters who book a second multi-day or weekly rental within 30 days (Target: >60%).

**On-Time Return Rate**: Percentage of rentals returned within the scheduled return window or grace period (Target: >90%).

**Student Satisfaction Score (CSAT)**: Post-rental survey rating measuring commute time saved and relief from Keke and heat friction (Target: ≥ 4.5 / 5.0).

## Phased Rollout Plan
**Phase 1**: Campus Pilot (Weeks 1–4): Deploy 50 bicycles across 3 high-friction hubs (Ameyo Hall, Cafeteria Axis, and a distant hall cluster) offering 3-day and 7-day rentals to validate pricing, lock durability, and attendant workflows.

**Phase 2**: Campus-Wide Expansion (Months 2–3): Scale the fleet to 200+ bicycles across all major male and female halls and academic complexes, introducing 14-day and 30-day exam passes alongside in-app extensions.

**Phase 3**: Optimization & Campus Integration (Semester 2+): Integrate campus smart-ID tap checkouts, expand covered bicycle parking racks across lecture blocks, and use historical route demand data to automate hub rebalancing.
## Fleet Management & Administration
**Live Fleet Dashboard**: As a Fleet Operations Manager, I want to view the real-time status of every bicycle (Available, Rented, Overdue, Under Maintenance), so that I can monitor utilization and redistribute bikes across busy hubs.

**Automated Expiry & Overdue Alerts**: As an Ops Manager, I want the system to send automated reminders to students before their rental expires—and automatically calculate late fees if overdue—so that fleet turnover stays predictable without manual follow-ups.

**Maintenance & Repair Tracking**: As a Maintenance Technician, I want to log repairs, spare part replacements, and service checks against specific bicycle serial numbers, so that unsafe bicycles are locked from booking until cleared.

## Core Features & Functional Requirements
**University Identity Verification**: Validates student matriculation numbers and campus email addresses during onboarding, linking every rental to a verified student record and hall of residence.

**Tiered Multi-Day Booking Engine**: Supports 3-day, 7-day, 14-day, and 30-day rental tiers with discounted weekly rates, automatic refundable caution deposit handling, and a 10-minute checkout inventory hold.

**Hub Check-In & Check-Out Portal**: Lightweight mobile interface for hub attendants to scan student QR codes, log bicycle and lock serial IDs, record pre- and post-ride inspection checklists, and complete handovers.

**Automated Notification System**: Sends SMS, email, and push notifications for booking confirmations, pickup windows, 24-hour and 2-hour expiry warnings, overdue notices, and maintenance swap approvals.

**Issue Reporting & Maintenance Workflow**: Enables students to submit photo-backed mechanical reports and immediately flags affected bicycles as unavailable in the admin dashboard until serviced.

**Usage & Demand Analytics**: Tracks peak booking periods (such as mid-semester tests and exams) and high-demand hubs to guide fleet expansion and staffing schedules.

## Stake holders:
**University Administration & Student Affairs Division**: Approves campus-wide operational policies, designated cycling lanes, parking zones, and student liability agreements.

**Babcock University Security Services**: Enforces campus traffic rules, prevents bicycle theft or unauthorized off-campus removal, and assists with incident resolution.

**Facilities & Works Department**: Allocates physical space for pickup/drop-off hubs, installs covered bicycle racks, and maintains campus road signage.

**Student Union / Hall Representatives (BUSA)**: Advocates for student pricing affordability, gathers feedback on hub placement, and promotes campus adoption.

**University IT & Finance Departments**: Supports student matriculation/email verification integration, payment gateway settlement, and security deposit reconciliation.

**Existing Campus Transport Operators (Keke Association)**: Key operational stakeholder whose routes and hub zones must be coordinated alongside bicycle parking hubs to prevent traffic congestion.

## User Stories
### Student Onboarding & Verification:
**Account Registration**: As a Babcock University student, I want to register on the platform using my university email and matriculation number, so that my identity is verified and tied to my campus residence profile.
**Safety & Liability Agreement**: As a first-time renter, I want to review and digitally sign the campus bicycle safety rules and liability terms, so that I understand approved riding routes, designated parking zones, and damage policies before riding.

## Non-Functional Requirements
**Performance & Low-Bandwidth Resilience**: Campus mobile data fluctuates around hostels and academic blocks. Core booking screens must load within 3 seconds on 3G/4G connections, and active booking QR codes/PINs must be cached offline for seamless hub pickups.

**Availability & Reliability**: The platform must maintain 99.5% uptime during active academic semesters, particularly during peak morning rush (7:00 AM – 9:00 AM) and exam weeks.

**Security & Data Privacy**: All digital payments must be processed via PCI-DSS compliant gateways. Student records (matriculation numbers, phone numbers, and hall details) must be encrypted in transit and at rest, with role-based access control restricting sensitive data to authorized campus administrators.

**Usability & Accessibility**: Mobile-first responsive interface requiring minimal onboarding friction—a verified student should be able to complete a multi-day booking in under 2 minutes.

**Scalability**: System architecture must support an initial pilot of 50–100 bicycles across 3–4 hubs and scale smoothly to 500+ bicycles across all residential halls and faculties without re-architecting.

## Scope & Priorities
**In-Scope (MVP - Phase 1)**
***P0 (Must-Have)***:

- Student onboarding and verification via Babcock University email (@student.babcock.edu.ng) and matriculation number.

- Real-time bicycle availability view per campus hub.

- Multi-day and weekly booking engine (3-day, 7-day, and 14-day tiers) with refundable caution deposit handling.

- Digital payment integration (bank transfer, USSD, debit card).

- Hub attendant QR/PIN check-in, condition inspection checklist, and return sign-off portal.

- Admin fleet dashboard tracking bicycle status (Available, Rented, Overdue, Under Maintenance).

***P1 (Should-Have):***

-Automated SMS/email/push reminders (booking confirmation, 24-hour and 2-hour expiry alerts, overdue notices).

- In-app rental extension workflow.

- Mid-rental mechanical issue reporting and hub swap workflow.

***P2 (Nice-to-Have):***

-Demand and route analytics dashboard for peak-period fleet rebalancing.

-Campus smart-ID tap integration at hub terminals.

**Out-of-Scope (Phase 1)**
- Per-minute or hourly dockless/GPS-unlocked rentals (the system relies on multi-day hub-to-hub rentals with physical locks).

- Off-campus riding or external town rentals outside Babcock University premises.

- Native iOS/Android app store releases (MVP will launch as a mobile-first Progressive Web App to avoid app-store friction and save student device storage).

## Acceptance Criteria
**Student Verification**: Users cannot reserve a bicycle until their @student.babcock.edu.ng email is verified via OTP and their matriculation number and Hall of Residence are saved to their profile.

**Inventory Locking & Booking**: Selecting a hub and rental tier holds an available bicycle for 10 minutes during checkout; completing payment generates a unique booking QR code, 6-digit PIN, and digital receipt within 5 seconds.

**Pickup & Inspection Handover**: Scanning a valid QR code at the designated hub displays the student's photo/matriculation ID to the attendant, logs the assigned bicycle and lock serial IDs, and requires both parties to confirm baseline condition before starting the rental timer.

**Rental Extension**: An active renter can extend their booking up to 6 hours before expiration, provided the bicycle is not reserved by a waitlist, with prorated fees charged immediately and the return deadline updated in real time.

**Breakdown & Swap**: Submitting an in-app mechanical issue ticket flags the current bicycle as "Under Maintenance" upon hub drop-off and allows the attendant to assign a replacement bicycle without charging a second rental fee.

**Return & Deposit Release**: When a hub attendant completes the post-ride inspection checklist and marks the bike returned, the rental status closes immediately, overdue timers stop, and the caution deposit refund workflow triggers automatically if no damage is logged.

**Overdue Notifications**: System triggers automated notifications 24 hours and 2 hours prior to expiration, applies a configurable 1-hour grace period, and automatically calculates hourly/daily late fees once the grace period expires.

## Assumptions & Open Questions
**Assumptions**
- Campus Infrastructure: Babcock University management will approve designated, covered bicycle parking racks at key hubs (e.g., Ameyo Hall, Cafeteria Axis, and distant residential clusters) prior to launch.

- Physical Security: Heavy-duty U-locks or chain locks issued with each bicycle, combined with campus gate security checks, are sufficient to prevent theft without requiring expensive real-time GPS trackers on every frame during the pilot.

- Student Smartphone Access: Over 90% of target students own an internet-enabled smartphone capable of accessing a mobile web app and displaying a QR code.

- Staffing Model: Hubs will be staffed during operating hours (e.g., 6:30 AM – 8:00 PM) by trained student work-study attendants or dedicated campus operations personnel.

**Open Questions**
- Caution Deposit Amount & Refund Timeline: What refundable deposit amount balances theft/damage deterrence without pricing out average students, and how quickly can the finance/payment gateway process automated refunds?

- Overnight & Curfew Policies: Are students permitted to keep rented bicycles parked at their residential halls overnight, or must all bikes be checked into a hub before campus curfew?

- Keke Association Coordination: Which specific campus lanes or drop-off zones need clear demarcation to prevent friction between bicycle riders and existing Keke operators?

- Damage Liability Thresholds: How will normal wear-and-tear (e.g., punctured tubes from campus roads) be distinguished from student negligence during post-ride hub inspections?
