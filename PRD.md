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

** Facilities & Works Department**: Allocates physical space for pickup/drop-off hubs, installs covered bicycle racks, and maintains campus road signage.

**Student Union / Hall Representatives (BUSA)**: Advocates for student pricing affordability, gathers feedback on hub placement, and promotes campus adoption.

**University IT & Finance Departments**: Supports student matriculation/email verification integration, payment gateway settlement, and security deposit reconciliation.

**Existing Campus Transport Operators (Keke Association)**: Key operational stakeholder whose routes and hub zones must be coordinated alongside bicycle parking hubs to prevent traffic congestion.

## User Stories
### Student Onboarding & Verification:
**Account Registration**: As a Babcock University student, I want to register on the platform using my university email and matriculation number, so that my identity is verified and tied to my campus residence profile.
