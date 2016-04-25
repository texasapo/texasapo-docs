# Girl Scout University Website User Guide
Welcome! This guide is for UTGSU staff to handle event registrations.

This document was originally written by Eric J Nguyen, Spring 2016 Webmaster, Cavendar Pledge Class (Spring 2015).

## Changes

If this document is out of date, **please update it**. You should also add an entry to the changelog in this section, following the format.

````
2016-04-25: [Eric J Nguyen][me at eric-nguyen dot com] Added contents and changes sections.
2016-03-30: [Eric J Nguyen][me at eric-nguyen dot com] Initial Version.
````
## Contents
<!-- MarkdownTOC -->

- [Prerequisites](#prerequisites)
- [Warnings](#warnings)
- [Setup](#setup)
   - [Creating a UTGSU Staff Account](#creating-a-utgsu-staff-account)
   - [Deactivating a UTGSU Staff Account](#deactivating-a-utgsu-staff-account)
   - [How Do I Edit This Guide?](#how-do-i-edit-this-guide)
- [Getting Started](#getting-started)
   - [Setting the Event Date\(s\)](#setting-the-event-dates)
   - [Adding a Category](#adding-a-category)
   - [Adding an Event](#adding-an-event)
- [Opening/Closing Registration](#openingclosing-registration)
   - [Opening Registration](#opening-registration)
   - [Closing Registration](#closing-registration)
- [Making Event or Class Changes](#making-event-or-class-changes)
   - [Modifying an Event or Class](#modifying-an-event-or-class)
   - [Deleting an Event or Class](#deleting-an-event-or-class)
- [Making Registration Changes](#making-registration-changes)
   - [Confirming Payments](#confirming-payments)
   - [Changing Attendee Names](#changing-attendee-names)
   - [Adding and Dropping Classes](#adding-and-dropping-classes)
   - [Manually Adding a Registration](#manually-adding-a-registration)
   - [Fully Cancelling a Registration](#fully-cancelling-a-registration)
   - [Partially Cancelling a Registration](#partially-cancelling-a-registration)
   - [Modifying User Details](#modifying-user-details)
- [Preparing for Girl Scout University](#preparing-for-girl-scout-university)
   - [Printing Event Packets, Course Schedules, and a Master Attendee List](#printing-event-packets-course-schedules-and-a-master-attendee-list)
   - [Verifying Permission Forms](#verifying-permission-forms)
   - [Checking In Users](#checking-in-users)
   - [Add User Comments](#add-user-comments)

<!-- /MarkdownTOC -->
<a name="prerequisites"></a>
## Prerequisites

 * A UTGSU Staff account (contact the Texas APO Webmaster) to get one. If you are the webmaster, instructions are below for creating a UTGSU Staff account.
 * Reading and understanding the entire [Warnings](#warnings) section.


<a name="warnings"></a>
## Warnings

 * **Never delete a user account** as this permenantly deletes a ton of information. Instead, [deactivate/suspend the account if no longer needed](#deactivating-a-utgsu-staff-account).
 * **Never delete an event (class)** once someone has registered for it. See [Deleting an Event or Class](deleting-an-event-or-class).
 * **Never delete a user's booking or payment** as will cause bookings and payments to go unaccounted for. See [Making Registration Changes](#making-registration-changes) for how to handle this case.
 * You don't need to delete previous year's stuff, including old classes, registrations, etc. This system was designed to work for multiple years.


<a name="setup"></a>
## Setup

<a name="creating-a-utgsu-staff-account"></a>
### Creating a UTGSU Staff Account
You'll need to be logged in (probably as **admin**) to create a UTGSU Staff Account.
 * Go to **Users** > **Add New**.
 * Fill in the **Username** and **Email** fields.
 * Under **Role**, select **UTGSU Staff**.
 * Click **Add New User**.

At this point, the user will receive an email about their account creation, as well as a link to set their password.

<a name="deactivating-a-utgsu-staff-account"></a>
### Deactivating a UTGSU Staff Account
 * Find the associated user under **Users** > **All Users** and click on their **Bookings**.
 * Click **Edit User** at the top.
 * Under **Name** change the **Role** to **-- No role for this site --**.
 * When you're done, click **Update User** at the bottom.

<a name="how-do-i-edit-this-guide"></a>
### How Do I Edit This Guide?
 * This guide is written using GitHub Flavored Markdown. A good guide is [here](https://help.github.com/articles/about-writing-and-formatting-on-github/).

<a name="getting-started"></a>
## Getting Started

<a name="setting-the-event-dates"></a>
### Setting the Event Date(s)
Setting these dates affect pretty much everything else, including what events get included in print outputs.
 * There is a special **Girl Scout University** module. Under **Event Date**, set the **Event Start Date** and **Event End Date**. If the event is a single day, set the **Event Start Date** and **Event End Date** to the same date.
 * Click **Update Event Dates**.

<a name="adding-a-category"></a>
### Adding a Category
 * Go to **Events** > **Event Categories**.
 * Fill in: the **Name** and **Slug**
 * Click **Add New Event Category**.

<a name="adding-an-event"></a>
### Adding an Event
 * Go to **Events** > **Add Event**.
 * Fill in:
   * **Class Name** (under **Title**)
   * **Description**
   * **Date/Time** (under **When**)
   * **Room** (under **Location**). *Previously-used locations will automatically be filled in, or you can add a new entry for a new location.* The convention is to use **TBD** for a location that will be filled in later.
 * Check **Enable registration for this event**
   * **Edit** the Standard Ticket to set the **Price** and number of **Spaces**
 * Under **Event Options** set the **Booking Cut-Off Date** to be the end of registration.
 * Under **Attributes** set **Instructor** to be the teacher for the class. *This can be left blank and changed later.*
 * On the right sidebar, under **Event Categories**, select the **level(s)** that the badge is under.
 * Click **Preview** to see a draft. When you're satisfied, click **Publish**. Note that once you click **Publish**, registration is open for the course. If you want to wait, click **Save Draft** instead and publish it later.


<a name="openingclosing-registration"></a>
## Opening/Closing Registration

<a name="opening-registration"></a>
### Opening Registration
 * Once an event is published, registration for the class is technically open. You can avoid this by saving the event as a draft, instead of publishing it (see [Adding an Event](#adding-an-event)).

<a name="closing-registration"></a>
### Closing Registration
 * You close registration by closing registration for each event. Do this by editing each event (see [Modifying an Event or Class](#modifying-an-event-or-class)) and making the **Booking Cut-Off Date** some date/time in the past.


<a name="making-event-or-class-changes"></a>
## Making Event or Class Changes

<a name="modifying-an-event-or-class"></a>
### Modifying an Event or Class
 * Go to **Events** > **Events**.
 * Find the event and click **Edit** under it. *Note that only events in the future are shown.*
 * Make the edits that you want. Click **Preview** to see a draft. When you're satisfied, click **Update**.

<a name="deleting-an-event-or-class"></a>
### Deleting an Event or Class
You should never delete a class once someone has registered for it, even if the event is in error. It is preferred, whenever possible, to simply change the event details to suit (see [Modifying an Event or Class](#modifying-an-event-or-class)).

*This also applies to an event or class from previous years. For these events, you can leave them as is. They'll be hidden from the backend and the user, for the most part.*

If you still really want to delete an event or class:
 * First, make sure that there are no confirmed or pending registrations remaining for this class (see [Fully Cancelling a Registration](fully-cancelling-a-registration)).
 * Find and **Edit** the event.
 * On the right-hand side, under **Publish**, click **Move to Trash**.


<a name="making-registration-changes"></a>
## Making Registration Changes
Note that, although a user may register multiple classes in a single transaction, a separate registration is processed for each unique class that the user registers for, with possibly multiple people being registered for a class under a single registration.

The instructions below assume a registration being a (possibly multi-seat) booking of a single event or class.

<a name="confirming-payments"></a>
### Confirming Payments
Note that PayPal payments from user-initiated registrations are automatically confirmed. No action needs to be taken by the UTGSU Staff to confirm these types of registrations. The instructions below are for confirming offline (check) payments or for confirming bookings that are initiated by UTGSU Staff.
 * Find and **Edit/View** the associated **booking**. You should be on an **Edit Booking** page.
 * Under **Booking Details**, next to **Status**, click **Change**.
 * Change the **Status** to **Approved**.
 * Click **Submit Changes**.

<a name="changing-attendee-names"></a>
### Changing Attendee Names
 * Find and **Edit/View** the associated **booking**. You should be on an **Edit Booking** page.
 * Under **Booking Details**, click **Modify Booking**.
 * Change the applicable names.
 * Click **Submit Changes**.

<a name="adding-and-dropping-classes"></a>
### Adding and Dropping Classes
 * To add/drop classes, you'll need to perform the drop operation (see [Fully Cancelling a Registration](fully-cancelling-a-registration) or [Partially Cancelling a Registration](#partially-cancelling-a-registration)), followed by the add operation (see [Manually Adding a Registration](#manually-adding-a-registration)).

<a name="manually-adding-a-registration"></a>
### Manually Adding a Registration
If you encounter an error through the steps below, you may need to temporarily adjust the **Booking Cut-Off Date** to some date/time in the future and/or add more spaces under **Modifying an Event or Class** make the change. If you adjust the **Booking Cut-Off Date**, be sure to adjust it back to prevent people from spuriously registering.

 * Find the specified class under **Events** and click **Bookings**.
 * Click **Add Booking**.
 * Select the number of **spaces** and enter each attendee's **First Name** and **Last Name**.
 * Select the **Username** that this registration will be under.
 * If this registration is serving as the **add** for an **add/drop** that they've previously paid for:
   * Enter **0.00** for **Amount Paid** and check **Fully Paid**.
   * Click **Register**.
 * If the registration is awaiting payment:
   * Leave **Amount Paid** blank and **Fully Paid** unchecked.
   * Click **Register**.
   * At this point, the registration will be in a **pending** state, until a UTGSU Staff user **confirms** their registration (see [Confirming Payments](#confirming-payments)).
   * If the parent wishes to pay via PayPal, have them manually [send money](https://www.paypal.com/webapps/mpp/send-money-online) to the UTGSU PayPal account. *Unlike normal PayPal-based registrations, this registration will need to be manually confirmed.*
   * If the parent wishes to pay by check, inform the parent about their need to mail in a check and that we'll confirm registration once received.
   * Once you receive payment, be sure to see [Confirming Payments](#confirming-payments).

<a name="fully-cancelling-a-registration"></a>
### Fully Cancelling a Registration
*Any applicable refunds will need to be manually handled (either from within PayPal or through a mailed check).*

 * Find and **Edit/View** the associated **booking**. You should be on an **Edit Booking** page.
 * Under **Booking Details**, next to **Status**, click **Change**.
   * If we have received previously received payment from them, change the status to **Cancelled**.
   * If we did not receive payment from them, change the status to **Rejected**.
 * Click **Submit Changes**.

<a name="partially-cancelling-a-registration"></a>
### Partially Cancelling a Registration
*Any applicable refunds will need to be manually handled (either from within PayPal or through a mailed check).*

 * Find and **Edit/View** the associated **booking**. You should be on an **Edit Booking** page.
 * Under **Booking Details**, change the number of spaces to the number that remain. *You may need to shift the names around to ensure that they don't get removed.*
 * Click **Submit Changes**.

<a name="modifying-user-details"></a>
### Modifying User Details

 * Find the associated user under **Users** > **All Users** and click on their **Bookings**.
 * Click **Edit User** at the top.
 * Scroll all the way to **Additional Capabilities**. Here, you can edit their **Address**, **Contact Phone Number**, etc.
 * When you're done, click **Update User**.


<a name="preparing-for-girl-scout-university"></a>
## Preparing for Girl Scout University
The big thing here is handling registrations that need attention. These will primarily be ones where we haven't received payment yet. Take care of these before printing anything out (see [Confirming Payments](#confirming-payments) or [Fully Cancelling a Registration](fully-cancelling-a-registration)).

<a name="printing-event-packets-course-schedules-and-a-master-attendee-list"></a>
### Printing Event Packets, Course Schedules, and a Master Attendee List

 * There is a special **Girl Scout University** module. Under **Generate Event Printouts**, there is a separate button (or message) for each action.

<a name="verifying-permission-forms"></a>
### Verifying Permission Forms

 * Find the associated user under **Users** > **All Users** and click on their **Bookings**.
 * Under **Personal Details** next to **Permission Forms Verified**, click **Verify Permission Forms**.

<a name="checking-in-users"></a>
### Checking In Users

 * Find the associated user under **Users** > **All Users** and click on their **Bookings**.
 * Under **Personal Details** next to **Checked In**, click **Check In User**.

<a name="add-user-comments"></a>
### Add User Comments

 * Find the associated user under **Users** > **All Users** and click on their **Bookings**.
 * Under **Personal Details** next to **Comments**, add your comment.
 * When you're done,  click **Update Comments**.