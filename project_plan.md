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

Note US 2.02.2 and US 2.02.3 will have to wait to be done since requires location tracking which isn't done in this sprint, 
### User Stories
| User Stories | Story Points |
| ------------ | ------------ |
| SETUP - Setting up dev environment | 4 |
| US 1.01.1 - Senior Onboarding | 6 |
| US 1.01.2 - Senior Email Verification | 4 |
| US 1.01.3 - Senior Reset Password | 5 |
| US 1.02.1 - Senior Profile Details | 3 |
| US 1.02.2 - Senior Photo Upload | 3 |
| US 1.02.3 - Senior Update Profile | 3 |
| US 1.03.1 - Main Dashboard for seniors | 3 |
| US 1.03.2 - Senior View List Companions/Volunteers | 5 |
| US 1.03.3 - Senior Profile Clicking | 3 |
| US 1.04.1 - Matching and Accessibility preferences for Seniors | 3 |
| US 1.04.2 - Senior Volunteer Companion Recommendations | 6 |
| US 1.04.3 - Senior Accessibility Preferences | 4 |
| US 2.01.1 - Desktop Sign-in with MFA | 8 |
| US 2.01.2 - Session Management & Timeout | 3 |
| US 2.02.1 - Search Users by Username/Email | 3 |
| US 2.03.1 - Registration Review Queue | 4 |
| US 2.03.2 - Approve / Reject / Request Info | 3 |
| US 3.01.1 – Volunteer Profile Creation | 3 |
| US 3.01.2 – Languages | 3 |
| US 3.01.3 – Skills and Interests | 5 | 
| US 3.01.4 – Prior Experience | 3 |
| US 3.01.5 – Certifications and Training | 8 |

19 total + half of US 3 = 25
25 / 7 = about 4 each

unironically all of these are in chronological order of US but it works out pretty nicely with most of the work in each group correlating in some way making doing the US for your group easier as opposed to giving some of those US to a different group

GROUP 1: US 1.01.1, US 1.01.2, US 1.01.3 => SP 15, Munib

GROUP 2: US 1.02.1, US 1.02.2, US 1.02.3 => SP 13, Rishh

GROUP 3: US 1.03.1, US 1.03.2, US 1.03.3 => SP 12, Daniel (note this individual will have to wait for US 3 people to do some work before US 1.03.2 and US 1.03.3 can be done)

GROUP 4: US 1.04.1, US 1.04.2, US 1.04.3 => SP 13, Zaid (have to wait for group 3 to create dashboard UI)

GROUP 5: US 2.01.1, US 2.01.2 => SP 11, Divit (this one has initial admin interface setup)
GROUP 6: US 2.02.1, US 2.03.1, US 2.03.2 => SP 11, Devon

GROUP 7: US 3.01.1, US 3.01.2, US 3.01.3 => SP 11, Dina


### Tasks
| Task | Related US | Assigned To | Due Data|
| -- | -- | -- | -- |
| Configure development environment (IDE, Git, dependencies) | SETUP | Everyone | Oct 5 |
| Implement API endpoint | US 1.01.1 | Munib | Oct 1 |
| Implement Initial Backend Classes for OOP | SETUP | Munib | Oct 1 |
| Create UI for signup/login screen | US 1.01.1 | Munib | Oct 1 |
| Create verify account screen | US 1.01.2 | Munib | Oct 9 |
| Configure signup endpoint to send verification email with code | US 1.01.2 | Munib | Oct 9 |
| Configure app and backend to give access after correct code is entered | US 1.01.2 | Munib | Oct 9 |
| Add forgot password button to signup/login screen | US 1.01.3 | Munib | Oct 9 |
| Create forgot password screen | US 1.01.3 | Munib | Oct 9 |
| Create API endpoint for sending password reset emails | US 1.01.3 | Munib | Oct 9 |
| Create webpage for resetting password | US 1.01.3 | Munib | Oct 9 |
| Setup database schema for senior profiles | US 1.02.1 | Rishh | Oct 9 |
| Build UI for entering profile details | US 1.02.1 | Rishh | Oct 9 |
| Add backend validation for profile details | US 1.02.1 | Rishh | Oct 9 |
| Create API endpoint for handling senior profile details | US 1.02.1 | Rishh | Oct 9 |
| Implement photo upload component in profile setup and edit profile screens | US 1.02.2 | Rishh | Oct 9 |
| Store uploaded photo in database / storage | US 1.02.2 | Rishh | Oct 9 |
| Add “edit profile” UI | US 1.02.3 | Rishh | Oct 9 |
| Create dashboard UI for seniors with companion and volunteer tabs| US 1.03.1 | Daniel | Oct 9 |
| Create companion and volunteer list screens | US 1.03.2 | Daniel | Oct 9 |
| Have each companion/volunteer in list show name, profile picture, etc | US 1.03.2 | Daniel | Oct 9 |
| Fetch and display senior companion/volunteer list | US 1.03.2 | Daniel | Oct 9 |
| Enable clicking companion/volunteer profiles to view details | US 1.03.3 | Daniel | Oct 9 |
| Create profile screen | US 1.03.3 | Daniel | Oct 9 |
| Add preferences tab to dashboard screen | US 1.04.1 | Zaid | Oct 9 |
| Add preference screen for editing and saving senior preferences | US 1.04.1 | Zaid | Oct 9 |
| Configure senior's database schema for storing senior preferences | US 1.04.1 | Zaid | Oct 9 |
| Add backend validation for senior preferences | US 1.04.1 | Zaid | Oct 9 |
| Create recommended matches tab in dashboard | US 1.04.2 | Zaid | Oct 9 |
| Implement algorithm for matching based on senior preferences (Chatgpt possibly?) | US 1.04.2 | Zaid | Oct 9 |
| Have each companion/volunteer in list show name, profile picture, companion/volunteer, and a matching detail | US 1.04.2 | Zaid | Oct 9 |
| Create app settings screen | US 1.04.3 | Zaid | Oct 9 |
| Add accessability options to app setting screen (text size, color modes)| US 1.04.3 | Zaid | Oct 9 |
| Configure saving of accessability settings | US 1.04.3 | Zaid | Oct 9 |
| Create admin sign-in screen (django gives a default one) | US 2.01.1 | Divit | Oct 1 |
| Create API endpoint to signin as admin (django gives a default one /admin) | US 2.01.1 | Divit | Oct 1 |
| Create a OTP screen which accepts a OTP | US 2.01.1 | Divit | Oct 12 |
| Create a method to generate and allow only the admin to access the OTP | US 2.01.1 | Divit | Oct 12 |
| Session timeout & auto-logout handling | US 2.01.2 | Divit | Oct 9 |
| Create admin dashboard screen to get to other screens | US 2.01.2 | Divit | Oct 1 |
| Create admin screen to search for users | US 2.02.1 | Devon | Oct 9 |
| Implement search users by username/email | US 2.02.1 | Devon | Oct 9 |
| Build registration review queue dashboard | US 2.03.1 | Devon | Oct 9 |
| Update database schema to store user registrations | US 2.03.1 | Devon | Oct 9 |
| Update app so access is only allowed after registration is accepted by admin | US 2.03.1 | Devon | Oct 9 |
| Approve/reject/request info workflow backend | US 2.03.2 | Devon | Oct 9 |
| Configure backend to allow sending reject/accept/request more info emails | US 2.03.2 | Devon | Oct 9 |
| Setup database schema for companion/volunteer profiles | US 3.01.1 | Dina | Oct 9 |
| Add companion/volunteer options for roles in profile details screen | US 3.01.1 | Dina | Oct 9 |
| Configure API endpoint for retreiving or writing companion/volunteer information to database | US 3.01.1 | Dina | Oct 9 |
| Add “languages spoken” input field | US 3.01.2 | Dina | Oct 9 |
| Adjust recommendation algorithm to take language spoken into consideration | US 3.01.2 | Dina | Oct 9 |
| Add skills and interest field on profile setup and profile edit | US 3.01.3 | Dina | Oct 9 |
| Add pre-defined list of skills and interests aswell as custom tags | US 3.01.3 | Dina | Oct 9 |
| Adjust recommendation algorithm to take the volunteer's/companion's skills into account | US 3.01.3 | Dina | Oct 9 |

NOTE AFTER THIS SPRINT THERE ARE 31 US LEFT, SO WE CAN MOVE SOME OF THESE TO SPRINT 3 IF WE REALLY WANT, JUST MOVE THE USER STORIES THAT DOESN'T HAVE ANY USER STORIES THAT DEPEND ON IT IN EACH GROUP TO SPRINT 3
## Sprint 3

| User Stories | Story Points |
| ------------ | ------------ |
| US 3.01.4 – Prior Experience | 3 |
| US 3.01.5 – Certifications and Training | 8 |
| US 3.01.7 – Background Check Status | 8 |
| US 3.01.9 – Volunteer Status Badge | 3 |
| US 3.01.10 – Service Area Radius | 5 |
| US 3.02.2 – Manage Volunteer Sessions | 5 |
| US 3.02.5 – Log Service Hours | 3 |
| US 3.02.6 – Recognition Badges | 3 |
| US 3.02.7 – Rate and Review Sessions | 2 |
| US 4.2.1 — Smart Match Intake | 3 |
| US 4.2.2 — Reschedule & Cancellation Rules | 3 |
| US 4.6.1 — Payout Preferences & Statements | 7 |

## Sprint 4
| User Stories | Story Points |
| ------------ | ------------ |
| US 06.01.01 -  Senior Session Booking | 6 |
| US 06.01.02 - Companion and Volunteer Session Acceptance | 3 |
| US 06.01.03 - Reschedule Request | 5 |
| US 06.01.04 - Reschedule Accept | 3 |
| US 06.01.05 - Calendar Implementation | 7 |
| US 06.01.07 - Automated Reminders | 7 |
| US 06.02.03 - Texting Between Users | 7 |
| US 06.03.01 - Companion and Volunteer Reviews | 3 |
| US 06.03.02 - Viewing Companion and Volunteer Ratings | 3 |
| US 06.03.03 - Companion and Volunteer Recommendation Via Rating | 5 |
| US 06.04.01 - User Encrypted Information | 5 |
| US 06.04.02 - User Privacy Controls | 4 |
| US 06.05.01 - Payment of Companions | 7 |
| US 06.05.02 - Receivement of Invoice | 4 |
| US 06.05.03 - Receivement of Receipt | 4 |

## Sprint 5
| User Stories | Story Points |
| ------------ | ------------ |
| US 07.01.03 - Admin Geo-Tracking | 6 |
| US 07.01.05 - Out-of-Schedule Activities | 4 |
| US 07.01.06 - Geo-Fenced Safe Zone | 4 |
| US 07.01.07 - Geo-Fence Violations | 6 |
| US 2.02.2 - Display Live/Last Known Location | 6 |
| US 2.02.3 - Consent-Gated Location Access | 6 |



