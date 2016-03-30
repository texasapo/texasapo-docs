# Girl Scout University Website User Guide

This guide is for UTGSU staff to modify the website.


## Prerequisites

 * A UTGSU Staff account (contact the Texas APO Webmaster) to get one. If you are the webmaster, instructions are below for creating a UTGSU Staff account.

## Warnings

 * **Never delete a user account** as this permenantly deletes a ton of information. Instead, deactivate/suspend the account if no longer needed under **Users**.
 * **Never delete an event (class)** once someone has registered for it. See **Deleting an Event or Class**.
 * **Never delete a user's booking or payment** as this may cause payments to go unaccounted for. See **Making Changes** for how to handle this case.

## Starting Up

### Creating a UTGSU Staff Account
You'll need to be logged in (probably as **admin**) to create an account.
 * Go to **Users** > **Add New**.
 * Fill in the **Username** and **Email** fields.
 * Under **Role**, select **UTGSU Staff**.
 * Click **Add New User**.

At this point, the user will receive an email about their account creation, as well as a link to set their password.

### Adding a Category
 * Go to **Events** > **Event Categories**.
 * Fill in: the **Name** and **Slug**
 * Click **Add New Event Category**.

### Adding an Event
 * Go to **Events** > **Add Event**.
 * Fill in:
   * **Class Name** (under **Title**)
   * **Description**
   * **Date/Time** (under **When**)
   * **Room** (under **Location**). *Previously-used locations will automatically be filled in, or you can add a new entry for a new location.*
 * Check **Enable registration for this event**
   * **Edit** the Standard Ticket to set the **Price** and number of **Spaces**
 * Under **Event Options** set the **Booking Cut-Off Date** to be the end of registration.
 * Under **Attributes** set **Instructor** to be the teacher for the class. *This can be left blank and changed later.*
 * On the right sidebar, under **Event Categories**, select the **level(s)** that the badge is under.
 * Click **Preview** to see a draft. When you're satisfied, click **Publish**. *Note that once you click **Publish**, registration is open for the course. If you want to wait, click *Save Draft* instead and publish it later.*

## Closing Registration
 * You close registration by closing registration for each event. Do this by editing each event (see **Modifying an Event or Class**) and making the **Booking Cut-Off Date** some date/time in the past.

## Making Event or Class Changes

### Modifying an Event or Class
 * Go to **Events** > **Events**.
 * Find the event and click **Edit** under it. *Note that only events in the future are shown.*
 * Make the edits that you want. Click **Preview** to see a draft. When you're satisfied, click **Update**.

### Deleting an Event or Class
*You should never delete a class once someone has registered for it, even if the event is in error. It is preferred, whenever possible, to simply change the event details to suit (see **Modifying an Event or Class**).*

*This also applies to an event or class from previous years. For these events, you can leave them as is. They'll be hidden from the backend and the user, for the most part.*

If you still really want to delete an event or class:
 * First, make sure that there are no confirmed or pending registrations remaining for this class (see **Fully Cancelling a Registration**).

### Modifying a Registration
Note that, although a user may register multiple classes in a single transaction, a separate registration is processed for each unique class that the user registers for, with possibly multiple people being registered for a class under a single registration.

The instructions below assume a registration being a (possibly multi-seat) booking of a single class.

## Making Registration Changes

#### Changing Attendee Names
 * Find and **Edit/View** the associated **booking**. You should be on an **Edit Booking** page.
 * Under **Booking Details**, click **Modify Booking**.
 * Change the applicable names.
 * Click **Submit Changes**.

#### Manually Adding a Registration
*If you encounter an error through the steps below, you may need to temporarily adjust the **Booking Cut-Off Date** to some date/time in the future and/or add more spaces under **Modifying an Event or Class** make the change. If you adjust the **Booking Cut-Off Date**, be sure to adjust it back to prevent people from spuriously registering.*
 * Find the specified class under **Events** and click **Bookings**.
 * Click **Add Booking**.
 * Select the number of **spaces** and enter each attendee's **First Name** and **Last Name**.
 * Select the **Username** that this registration will be under.
 * If this registration is serving as the **add** for an **add/drop** that they've previously paid for:
   * Enter **0.00** for **Amount Paid** and check **Fully Paid**.
   * Click **Register**.
 * If the registration is awaiting payment
   * Leave **Amount Paid** blank and **Fully Paid** unchecked.
   * Click **Register**.
   * At this point, the registration will be in a **pending** state, until a UTGSU Staff user **confirms** their registration (see **Confirming a Payment**). You should inform the parent about the need to submit a check payment and that we'll confirm registration once received.
   * *Once you receive payment, be sure to follow **Confirming a Payment**.*

#### Fully Cancelling a Registration
*Any applicable refunds will need to be manually handled (either from within PayPal or through a mailed check).*
 * Find and **Edit/View** the associated **booking**. You should be on an **Edit Booking** page.
 * Under **Booking Details**, next to **Status**, click **Change**.
   * If we have received previously received payment from them, change the status to **Cancelled**.
   * If we did not receive payment from them, change the status to **Rejected**.
 * Click **Submit Changes**.

#### Partially Cancelling a Registration
*Any applicable refunds will need to be manually handled (either from within PayPal or through a mailed check).*
 * Find and **Edit/View** the associated **booking**. You should be on an **Edit Booking** page.
 * Under **Booking Details**, change the number of spaces to the number that remain. *You may need to shift the names around to ensure that they don't get removed.*
 * Click **Submit Changes**.