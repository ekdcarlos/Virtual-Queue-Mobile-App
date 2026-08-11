# Virtual-Queue-Mobile-App

### Project Overview

### Problem Statement:
University students waste significant time waiting in physical queues at administrative offices including:
- Registry Office (course registration, transcripts)
- Finance Office (fee payments, receipts)
- Clinic (medical appointments)
- Accommodation Office (housing queries)
- Library (book borrowing/returns)

This leads to:
- **Lost study time** - Students spend 30-60 minutes daily standing in lines
- **Frustration and anxiety** - No way to know wait duration
- **Inefficiency** - Overcrowded service points during peak hours
- **Missed opportunities** - Students leave queues due to length, losing their spot

### Our Solution
A mobile application that allows students to:
- Join virtual queues remotely
- View real-time position and estimated wait time
- Receive notifications when it's their turn
- Leave or rejoin queues easily
- Rate service experiences
  

## Team Members ## 

| Name | GitHub Username | Reg No. |
|------|----------------|---------------------|
| Emmanuel Dena | @ekdcarlos | C025-01-0602/2023 |
| James Onyancha | @jimmyzzi | C025-01-0683/2023 |
| Isaac Ngatia | @iruka87 | C025-01-0642/2023 |
| Grace Ruguru | @grace001-dev | C025-01-0628/2023 |
| Esther Achieng | @EstherOwino | C025-01-0655/2023 |
| Derick Kipkoech | @Deroh14 | C025-01-0673/2023 |

Target Users
Primary Users
-	**University Students** – Need efficient access to administrative services without wasting valuable study time.
-	**First-Year Students** – Often unfamiliar with university processes and require clear guidance.
-	**International Students** – May need extra support navigating university systems.
Secondary Users
•	University Staff – Want better crowd management and service efficiency at their service points.
•	Administrators – Need data on service usage patterns to optimize operations.

 User Personas
Persona 1: Amara – The Busy Student
Age: 21 | Year: 3rd Year, Computer Science | Tech Comfort: High
Amara is a hardworking 3rd year student with a heavy academic workload. She balances 6 courses, group projects, and her final year research proposal. Her time is extremely valuable, and she gets frustrated when administrative tasks disrupt her study schedule.
Pain Points:
•	Wastes 1 hour daily standing in queues
•	Can't predict how long she'll wait
•	Misses valuable study time
•	Feels helpless not knowing queue status
Goals:
•	Minimize time spent waiting
•	Study during waiting periods
•	Know exactly when to arrive at service points
Quote: "I want to be productive during waiting time, not just stare at a wall."
Needs from App:
•	Accurate wait time estimation
•	Real-time position tracking
•	Flexible notification preferences
•	Quick join and leave options

Persona 2: Kevin – The Anxious First-Year
Age: 19 | Year: 1st Year, Business | Tech Comfort: Medium
Kevin recently joined the university and is still learning how everything works. He's often unsure about university procedures and feels nervous about making mistakes. He relies on his phone for many daily tasks but isn't a power user.
Pain Points:
•	Unfamiliar with university processes
•	Unsure which office to visit for what
•	Worries about being in the wrong queue
•	Nervous about speaking to staff
Goals:
•	Get clear, step-by-step guidance
•	Feel confident he's doing the right thing
•	Simple, uncluttered experience
Quote: "I just want to be sure I'm doing this right."
Needs from App:
•	Clear instructions at each step
•	Visual progress indicators
•	Office location and directions
•	Simple, uncluttered interface

**Key Features**
Service Discovery – Browse all service points with opening hours and locations
• Join Queue – Join a virtual queue with one tap
• Position Tracking – See real-time position and estimated wait time
• Smart Notifications – Get alerts when you're near the front (10, 5, 2 positions ahead)
• Queue History – View past visits, wait times, and ratings
• Service Rating – Rate your experience and provide feedback
• Location Info – View office locations and directions
• Peak Time Insights – Know when offices are busiest

 **Core User Scenarios**
**Scenario 1: Join a Virtual Queue**
1.User logs in with student ID
2.Browses or searches for a service point (e.g., Registry Office)
3.Views office details including location, hours, and current queue length
4.Taps "Join Queue"
5.Confirms the action
6.Views their position (#4 of 12) and estimated wait time
7.Receives notifications as their position advances
8.Gets a "Your Turn!" alert
9.Proceeds to the service point
10.Confirms completion and rates the experience

**Scenario 2: Cancel/Leave a Queue**
1.User is currently in a queue
2.Taps "Leave Queue" button
3.Receives a confirmation prompt ("Are you sure?")
4.Confirms cancellation
5.Receives feedback: "You've left the queue"
6.Returns to the dashboard

**Scenario 3: View History & Re-join**
1.User navigates to the History tab
2.Views past queue visits with dates, times, and ratings
3.Taps "Rejoin" button for a recent service
4.Confirms and joins the queue instantly
5.Views their new position

 **Functional Requirements**
**Authentication**
• Login with student ID and PIN
• Guest view for browsing (read-only)
**Service Discovery**
• Browse all service points
• Filter/search for specific offices
• View opening hours and locations
• See current queue length and estimated wait time
**Queue Management**
• Join a virtual queue
• View current position (#4 of 12)
• View estimated wait time
• Receive progress notifications (10, 5, 2 positions ahead)
• Receive "Your Turn!" alert
• Leave queue with confirmation
• View queue history

**Notifications**
• When 10 positions ahead
• When 5 positions ahead
• When 2 positions ahead
• "It's your turn" alert
• Service completion confirmation
• 5-minute reminder before turn
**Feedback & History**
• Rate service experience (⭐1-5)
• Provide optional feedback
• View past queue history
• Report issues
**Usability Requirements**
• Touch-Friendly Targets – All buttons ≥44px for easy tapping
• Clear Status Visibility – Queue position always visible
• Simple Flows – 3-step process: Select → Join → Confirm
• Clear Feedback – Every action has visible confirmation
• Error Prevention – Confirm before leaving critical queues
• Accessibility – High contrast, clear labels, screen reader compatible
• Consistent Navigation – Bottom tab bar for main sections
• Minimal Cognitive Load – One primary action per screen
## Usability Testing Summary

*Participants*

- 5 university students from various years and programs.

*Tasks Tested*

- Join a virtual queue.
- Monitor queue position.
- Cancel/leave a queue.
- View history and rejoin.
- Handle turn notifications.

*Results*

- *Task Completion Rate:* 92% (all tasks completed successfully).
- *Average Time on Task:* 45 seconds (initial prototype) → 28 seconds (after iteration).
- *User Satisfaction:* 4.3/5 average rating.

*Key Issues Identified & Resolved*

| Issue | Severity | Solution | Status |
|--------|----------|----------|--------|
| Inconsistent terminology ("Join Queue" vs "Check-in") | High | Used "Join Queue" everywhere | Resolved |
| Too many clicks to join (4–5 steps) | High | Added "Quick Join" widget on home | Resolved |
| Missing office location details | Medium | Added address and map pin | Resolved |
| Progress bar didn't animate | Medium | Added visual progression | Resolved |
| Peak times not shown | Low | Added busy hour indicator | Resolved |
| Rejoin process unclear | Medium | Added "Rejoin" button in history | Resolved |

## Technologies Used

- *Balsamiq* – Low-fidelity wireframing and prototyping.
- *GitHub* – Version control, collaboration, and submission.
- *GitHub Issues* – Task tracking and project management.
- *Google Docs* – Collaborative documentation.

## HCI Principles Applied

- *Visibility* – Queue position and wait time are always visible on the home screen.
- *Feedback* – Every action (join, leave, confirm) provides clear visual confirmation.
- *Consistency* – Same navigation patterns, button styles, and terminology throughout.
- *Constraints* – Confirmation dialogs prevent accidental queue exits.
- *Affordance* – Buttons are clearly tappable; notifications are prominent.
- *Mapping* – Queue position maps to the real-world waiting experience.
- *Error Prevention* – Confirm before leaving and before joining a queue.
- *Flexibility* – Multiple ways to join (Quick Join, Browse, Search).
- *Accessibility* – Large touch targets, high contrast, and clear labels.
- *Recognition over Recall* – Service list visible; no need to remember office names.

## Future Improvements

- *Admin Dashboard* – Allow staff to manage queues and view analytics.
- *Peak Time Analytics* – Show historical busy patterns.
- *Calendar Integration* – Sync with the university calendar.
- *Multi-Queue Management* – Join multiple queues simultaneously.
- *In-App Map* – Show directions to service points.
- *Email/SMS Notifications* – Backup notification methods.
- *Language Support* – Include local languages.
- *Offline Mode* – View saved queue information.
