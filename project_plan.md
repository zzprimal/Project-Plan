# Project Plan
## Sprint 1

### Tasks
| Task | Related US | Assigned To | Due Data|
| -- | -- | -- | -- |
| Project Requirement Document | Documentation | Everyone | Sept 21 |
| Software Design Document | Documentation | Munib, Divit, Daniel | Sept 25 |
| Project Management Document | Documentation | Dina, Zaid, Devon | Sept 25 |
| Teamwork Document | Documentation | Rishh | Sept 25 |
| Github Setup | Documentation | Rishh | Sept 25 |

## Sprint 2
Mostly just codebase setup, senior profile setup, setting up initial session scheduling functionality (but not implementing sessions just yet), senior browsing of companions and volunteers and profile viewing, companions and volunteers setting up availablility hours and other profile related things, and basic admin functionality. I grouped these user stories together below (see START GROUP), people who get a group with only 4 user stories have to do the SETUP task aswell (Note a group has 8 user stories but alot of these user stories are pretty equivalent or very close to equivalent which imo brings it down to 5 user stories). Also someone is going to get a headstart on implementing the map and map tracking functionality in this sprint, and someone is going to start implementing family functionality and that same person is going to implement searching functionality.

GROUP 1 IS GOOD

GROUP 2 IS GOOD

GROUP 3 US 2.07.1 might need changing since initial session setup might be late, push to sprint 3

There needs to be profile create US for companions

GROUP 4 you just start creating features for companions without doing US for companion profile creation, 
should just group together most of companion and volunteer US since they are mostly the same and shouldn't be
too much extra work, just accounting for an extra role 

GROUP 5 is probably a bit too much even with the duplicate user stories, GROUP 1 has to finish first which could take a while, after that GROUP 5 can get started but will have to wait for GROUP 4 to finish their volunteer (and probably since theyre so similar) companion functionality before they can fully implement sessions, to help get rid of US 06.03.01 and maybe US 4.2.1, seperate calendar functionality from US 06.01.01 and US 06.01.03 which will lower their story points and add calendar functionality for choosing dates as a seperate US. Also note US 3.02.2 is equivalent to the subtasks in US 6.01

GROUP 6 for senior searching functionality this will probably build ontop of the volunteer and companion list functionality of GROUP 2 (so maybe waiting for them to atleast get partially finished is a good idea), also maybe push back US 5.01.3 to Sprint 3

GROUP 7 might be a bit harsh but i think implementing the initial map functionality won't be to difficult this early on, for US 07.01.01 and 07.01.06 you would need to wait for GROUP 1 to complete senior profile setup, for US 07.01.04 you would also need to wait for GROUP 4

Overall 2 people probably would need to do the initial dev environment setup then start working on GROUP 1 and GROUP 2 US in parallel probably needing some synchronization (probably munib and divit since they seem to have the most chemistry), after that the rest of the work can mostly start with GROUP 4 starting, GROUP 7 can start, GROUP 6 can start, GROUP 3 can start. GROUP 5 might have to wait a bit for GROUP 4 to finish companion and volunteer profile creation so perferably whoever is doing GROUP 4 needs to finish that as early as possible, other than that they can start but they might be stressed for time which is why it's a good idea to get rid of some of their work load
### User Stories
| User Stories | Story Points |
| ------------ | ------------ |
| SETUP - Setting up dev environment | 4 |
| US 1.01.1 - Senior Onboarding (START GROUP 1) | 6 |
| US 1.02.1 - Senior Profile Details | 3 |
| US 1.02.2 - Senior Photo Upload | 3 |
| US 1.02.3 - Senior Update Profile | 3 |
| US 1.03.2 - Senior View List Companions/Volunteers (START GROUP 2) | 5 |
| US 1.03.1 - Main Dashboard for Seniors | 3 |
| US 1.03.3 - Senior Profile Clicking | 3 |
| US 06.03.02 - Viewing Companion and Volunteer Ratings | 3 |
| US 2.02.1 - Search Users by Username/Email (START GROUP 3) |
| US 2.03.1 - Registration Review Queue | 4 |
| US 2.03.2 - Approve / Reject / Request Info | 3 |
| US 2.01.2 - Session Management & Timeout | 3 |
| US 2.07.1 - Session Search | 5 |
| US 3.01.1 – Volunteer Profile Creation (START GROUP 4) | 3 |
| US 3.01.2 – Languages | 3 |
| US 3.02.1 – Manage Availability | 3 |
| US 4.1.2 — Availability Templates | 5 |
| US 06.01.01 - Senior Session Booking (START GROUP 5) | 6 |
| US 06.01.02 - Companion and Volunteer Session Acceptance | 3 |
| US 06.01.03 - Reschedule Request | 5 |
| US 06.01.04 - Reschedule Accept | 3 |
| US 06.03.01 - Companion and Volunteer Reviews | 3 |
| US 3.02.2 – Manage Volunteer Sessions | 5 |
| US 4.2.1 — Smart Match Intake | 3 |
| US 5.02.1 – Family Profile Creation (START GROUP 6) | 3 |
| US 5.02.2 - Family Senior Search | 4 |
| US 1.05.1 - Senior Profile Searching | 4 |
| US 5.02.3 – Family Senior Caregiver | 4 |
| US 5.01.3 – View Logs & Session History | 5 |
| US 07.01.01 - Geo-Tracking Activation (START GROUP 7) | 8 |
| US 07.01.06 - Geo-Fenced Safe Zone | 4 |
| US 07.01.04 - Location Proximity Threshold Filter | 7 |

Estimated sprint velocity:

### Tasks
| Task | Related US | Assigned To | Due Data|
| -- | -- | -- | -- |
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
| US 2.05.1 - Schedule Explorer (START GROUP 1) | 7 |
| US 2.06.3 - Acknowledge/Resolve Workflow | 3 |
| US 2.05.3 - Cancel/Reassign with Notifications | 3 |
| US 2.05.2 - Conflict Detection | 4 |
| US 2.07.2 - Session Metrics | 3 |
| US 1.01.2 - Senior Email Verification (START GROUP 2) | 4 |
| US 1.01.3 - Senior Reset Password | 5 |
| US 1.04.1 - Matching and Accessibility preferences for Seniors | 3 |
| US 1.04.2 Senior Volunteer Companion Recommendations | 6 |
| US 1.04.3 - Senior Accessibility Preferences | 4 |
| US 3.02.7 – Rate and Review Sessions (START GROUP 3) | 2 |
| US 3.01.3 – Skills and Interests | 5 |
| US 3.01.4 – Prior Experience | 3 |
| US 3.01.5 – Certifications and Training | 8 |
| US 3.02.4 – Secure Communication | 5 |
| US 06.05.01 - Payment of Companions (START GROUP 4) | 7 |
| US 06.05.02 - Receivement of Invoice | 4 |
| US 06.05.03 - Receivement of Receipt | 4 |
| US 4.6.1 — Payout Preferences & Statements | 7 |
| US 4.6.2 — Tax/Invoice Export | 5 |
| US 06.02.01 - Senior, Volunteer, and Companion Virtual Sessions (START GROUP 5) | 8 |
| US 5.01.4 – Monitor Virtual Sessions | 5 |
| US 06.02.02 - Family Attendable Virtual Sessions | 5 |
| US 3.02.3 – Virtual Session Participation | 5 |
| US 4.3.1 Session Timer & Notes Shortcut | 5 |
| US 5.01.1 – View & Approve Matches (START GROUP 6) | 5 |
| US 5.01.5 – Rate & Review Companions | 3 |
| US 6.06.01 SOS Button | 5 |
| US 5.01.6 – Receive Safety Alerts | 4 |
| US 07.01.05 - Out-of-Schedule Activities | 4 |
| US 5.01.2 – Real-Time Geo Alerts (START GROUP 7) | 4 |
| US 07.01.07 - Geo-Fence Violations | 6 |
| US 07.01.03 - Admin Geo-Tracking | 6 |
| US 07.01.02 - Family Member Geo-Tracking | 5 |

## Sprint 4
### User Stories
| User Stories | Story Points |
| ------------ | ------------ |
| US 2.01.1 - Desktop Sign-in with MFA (START GROUP 1) | 8 |
| US 2.02.2 - Display Live/Last Known Location | 6 |
| US 2.02.3 - Consent-Gated Location Access | 6 |
| US 2.08.4 - Receipts & Invoices Management (START GROUP 2) | 4 |
| US 2.08.3 - Reconciliation & Mismatch Flags | 3 |
| US 2.08.2 - Pay/Dispute/Hold | 4 |
| US 2.08.1 - Payable Generation | 5 |
| US 06.01.05 - Calendar Implementation (START GROUP 3) | 7 |
| US 06.01.06 - External Calendar Syncing | 8 |
| US 06.01.07 - Automated Reminders | 7 |
| US 4.1.1 — Calendar Sync & Reminders | 8 |
| US 06.02.03 - Texting Between Users (START GROUP 4) | 7 |
| US 06.04.02 - User Privacy Controls | 4 |
| US 06.04.01 - User Encrypted Information | 5 |
| US 3.01.7 – Background Check Status (START GROUP 5) | 8 |
| US 3.01.6 – References | 3
| US 3.01.9 – Volunteer Status Badge (START GROUP 6) | 3 |
| US 3.01.8 – Transportation Options | 5 |
| US 3.02.5 – Log Service Hours | 3 |
| US 3.02.6 – Recognition Badges | 3 |
| US 3.01.10 – Service Area Radius (START GROUP 7) | 5 |
| US 3.02.8 – Optional Payment and Billing | 5 |

## Sprint 5
### User Stories
| User Stories | Story Points |
| ------------ | ------------ |
| US 2.04.1 - Record Background Check Results (START GROUP 1) | 8 |
| US 2.06.1 - Safety Alert Inbox | 4 |
| US 2.06.2 - Alert Detail & Map Trace | 7 |
| US 2.06.4 - False Positive Classification | 3 |
| US 2.08.2 - Pay/Dispute/Hold (START GROUP 2) | 4 |
| US 06.03.03 - Companion and Volunteer Recommendation Via Rating (START GROUP 3) | 5 |
| US 4.5.1 — Structured Visit Notes | 4 |
| US 4.4.1 — Moderation & Report Abuse (START GROUP 4) | 5 |
| US 4.2.2 — Reschedule & Cancellation Rules (START GROUP 5) | 3 |