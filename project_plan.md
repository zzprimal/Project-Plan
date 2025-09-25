# Project Plan
## Sprint 1
### User Stories
| User Stories | Story Points |
|------------------------------|--------------------------|
| Project Requirement Document | 5 |
| Software Design Document | 8 |
| Project Management Document | 6 |
| Teamwork Document | 3 |
| Github Setup | 1 |

### Tasks
| Task | Related US | Assigned To | Due Data|
| -- | -- | -- | -- |
| Creating Initial User Stories | Project Requirement Document | Everyone | Sept 21 |
| Architecture Diagram | Software Design Document | Muneb | Sept 25 |
| Interaction Scenarios (UML SDs) | Software Design Document | David | Sept 25 |
| Wireframes | Software Design Document | ? | Sept 25 |
| Storymap | Project Management Document | Dina | Sept 25 |
| Project Plan | Project Management Document | Devon and Zaid | Sept 25 | 
| Team Canvas | Teamwork Document | Rish | Sept 25 |
| Belbin Roles | Teamwork Document | Rish | Sept 25 |
| Make Git Wiki | Github Setup | Rish | Sept 25 |
| Make Github Pages | Github Setup | Rish | Sept 25 |

## Sprint 2
Mostly just codebase setup, senior profile setup, setting up initial session scheduling functionality (but not implementing sessions just yet), senior browsing of companions and volunteers and profile viewing, companions and volunteers setting up availablility hours and other profile related things, and basic admin functionality. I grouped these user stories together below (see START GROUP), people who get a group with only 4 user stories have to do the SETUP task aswell (Note a group has 8 user stories but alot of these user stories are pretty equivalent or very close to equivalent which imo brings it down to 5 user stories). Also someone is going to get a headstart on implementing the map and map tracking functionality in this sprint, and someone is going to start implementing family functionality and that same person is going to implement searching functionality.
### User Stories
| User Stories | Story Points |
| ------------ | ------------ |
| SETUP - Setting up dev environment | 4 |
| US 1.01.1 - Senior Onboarding (START GROUP) |
| US 1.02.1 - Senior Profile Details |
| US 1.02.2 - Senior Photo Upload |
| US 1.02.3 - Senior Update Profile |
| US 1.03.2 - Senior View List Companions/Volunteers (START GROUP) |
| US 1.03.1 - Main Dashboard for Seniors |
| US 1.03.3 - Senior Profile Clicking |
| US 06.03.02 - Viewing Companion and Volunteer Ratings |
| US 2.02.1 - Search Users by Username/Email (START GROUP) |
| US 2.03.1 - Registration Review Queue |
| US 2.03.2 - Approve / Reject / Request Info |
| US 2.01.2 - Session Management & Timeout |
| US 2.07.1 - Session Search |
| US 3.01.1 – Volunteer Profile Creation (START GROUP) |
| US 3.01.2 – Languages |
| US 3.02.1 – Manage Availability |
| US 4.1 — Availability Management |
| US 4.1.2 — Availability Templates |
| US 06.01.01 - Senior Session Booking (START GROUP) |
| US 06.01.02 - Companion and Volunteer Session Acceptance |
| US 06.01.03 - Reschedule Request |
| US 06.01.04 - Reschedule Accept |
| US 06.03.01 - Companion and Volunteer Reviews |
| US 3.02.2 – Manage Volunteer Sessions |
| US 4.2 — Appointment Handling |
| US 4.2.1 — Smart Match Intake |
| US 5.02.1 – Family Profile Creation (START GROUP) |
| US 5.02.2 - Family Senior Search |
| US 1.05.1 - Senior Profile Searching |
| US 5.02.3 – Family Senior Caregiver |
| US 5.01.3 – View Logs & Session History |
| US 07.01.01 - Geo-Tracking Activation (START GROUP) |
| US 07.01.06 - Geo-Fenced Safe Zone |
| US 07.01.04 - Location Proximity Threshold Filter |


### Tasks
| Task | Related US | Assigned To | Due Data|
| Configure development environment (IDE, Git, dependencies) | SETUP | Everyone | Oct 5 |
| Setup database schema for senior profiles | US 1.02.1 | Munib | Oct 5 |
| Implement API endpoint | US 1.01.1 | Munib | Oct 5 |
| Create UI for senior onboarding | US 1.01.1 | Dina | Oct 6 |
| Build UI for entering profile details | US 1.02.1 | Dina | Oct 6 |
| Add backend validation for profile details | US 1.02.1 | Divit | Oct 6 |
| Implement photo upload component | US 1.02.2 | Divit | Oct 7 |
| Store uploaded photo in database / storage | US 1.02.2 | Divit | Oct 7 |
| Add “edit profile” UI | US 1.02.3 | Daniel | Oct 7 |
| Create dashboard UI for seniors | US 1.03.1 | Daniel | Oct 7 |
| Fetch and display senior companion/volunteer list | US 1.03.2 | Daniel | Oct 7 |
| Enable clicking senior profiles to view details | US 1.03.3 | Rish | Oct 8 |
| Add rating display for companions/volunteers | US 06.03.02 | Rish | Oct 8 |
| Implement search users by username/email | US 2.02.1 | Zaid | Oct 8 |
| Build registration review queue dashboard | US 2.03.1 | Devon | Oct 8 |
| Approve/reject/request info workflow backend | US 2.03.2 | Devon | Oct 9 |
| Session timeout & auto-logout handling | US 2.01.2 | Munib | Oct 9 |
| Implement session search feature | US 2.07.1 | Rish | Oct 9 |
| Volunteer profile creation form | US 3.01.1 | Zaid | Oct 9 |
| Add “languages spoken” input field | US 3.01.2 | Zaid | Oct 9 |
| Manage volunteer availability calendar | US 3.02.1 | Rish | Oct 10 |
| Availability templates feature | US 4.1.2 | Rish | Oct 10 |
| Senior session booking flow | US 06.01.01 | Dina | Oct 10 |
| Companion/volunteer session acceptance | US 06.01.02 | Daniel | Oct 10 |
| Reschedule request | US 06.01.03 | Devon | Oct 10 |
| Reschedule accept | US 06.01.04 | Devon | Oct 10 |
| Companion/volunteer review submission | US 06.03.01 | Dina | Oct 10 |
| Manage volunteer sessions dashboard | US 3.02.2 | Daniel | Oct 10 |
| Appointment handling backend | US 4.2 | Munib | Oct 10 |
| Smart match algorithm | US 4.2.1 | Divit | Oct 11 |
| Family profile creation form | US 5.02.1 | Zaid | Oct 11 |
| Family senior search | US 5.02.2 | Zaid | Oct 11 |
| Senior profile searching feature | US 1.05.1 | Zaid | Oct 11 |
| Family caregiver | US 5.02.3 | Daniel | Oct 11 |
| View logs & session history | US 5.01.3 | Munib | Oct 11 |
| Geo-tracking toggle (on/off) | US 07.01.01 | Divit | Oct 11 |
| Safe zone creation | US 07.01.06 | Devon | Oct 12 |
| Proximity threshold filter | US 07.01.04 | Daniel | Oct 12 |

## Sprint 3
Finishing the session stuff, more admin tasks, finish senior user stories (US 1.0), get started on implementing payment mechanisms, finish off volunteer user stories, start implementing video calls in the app, family related tasks in regards to their seniors safety, and finally some geolocation tasks for tracking and safety

### User Stories
| User Stories | Story Points |
| ------------ | ------------ |
| US 2.05.1 - Schedule Explorer (START GROUP) |
| US 2.06.3 - Acknowledge/Resolve Workflow |
| US 2.05.3 - Cancel/Reassign with Notifications |
| US 2.05.2 - Conflict Detection |
| US 2.07.2 - Session Metrics |
| US 1.01.2 - Senior Email Verification (START GROUP) |
| US 1.01.3 - Senior Reset Password |
| US 1.04.1 - Matching and Accessibility preferences for Seniors |
| US 1.04.2 Senior Volunteer Companion Recommendations |
| US 1.04.3 - Senior Accessibility Preferences |
| US 3.02.7 – Rate and Review Sessions (START GROUP) |
| US 3.01.3 – Skills and Interests |
| US 3.01.4 – Prior Experience |
| US 3.01.5 – Certifications and Training |
| US 3.02.4 – Secure Communication |
| US 06.05.01 - Payment of Companions (START GROUP) |
| US 06.05.02 - Receivement of Invoice |
| US 06.05.03 - Receivement of Receipt |
| US 4.6 — Payments & Compliance |
| US 4.6.1 — Payout Preferences & Statements |
| US 4.6.2 — Tax/Invoice Export |
| US 06.02.01 - Senior, Volunteer, and Companion Virtual Sessions (START GROUP) |
| US 5.01.4 – Monitor Virtual Sessions | 
| US 3.02.3 – Virtual Session Participation |
| US 4.3 — Virtual Session Tracking |
| US 5.01.1 – View & Approve Matches (START GROUP) |
| US 5.01.5 – Rate & Review Companions |
| US 6.06.01 SOS Button |
| US 5.01.6 – Receive Safety Alerts |
| US 07.01.05 - Out-of-Schedule Activities |
| US 5.01.2 – Real-Time Geo Alerts (START GROUP) |
| US 07.01.07 - Geo-Fence Violations |
| US 07.01.03 - Admin Geo-Tracking |
| US 07.01.02 - Family Member Geo-Tracking |