---
title: "How do I create a notification that is sent to students when their enrollment is cancelled by an administrator?"
description: "This is a template containing all the settings you need to create an automated notification to be sent to students when they are cancelled."
ispublished: yes
---

# How do I create a notification that is sent to students when their enrollment is cancelled by an administrator?

1. Input a name and description for the notification.
1. The trigger is when a student’s enrollment status is changed to cancelled. The Trigger Event is **Class Enrollment Cancelled**.
1. Add filters, for example you may want to set the Class Status to **Scheduled**, then nothing is sent for a class in another status.
1. An administrator cancels a student’s enrollment. The Triggered By is **Administrator**.
1. If this is only being sent to the enrolled student, then the To is **User**.
1. Fill in **From**and **Subject**. Add a **CC* as needed. 
1. Add **Calendar Integration** for the user to add an appointment for their class enrollment.
1. Uncheck **Enabled** until you are ready to test the notification.
1. Input your **text** with replacement text for the notification.
1. On the **Organization** tab, assign the organization(s) where the notification will be used.

### Additional Resources

For more information on enrollment notifications and descriptions of all the available fields, go to the article below.
[How do I create registration notifications?](/tms/tms-administrators/notifications/registration-notification.md)