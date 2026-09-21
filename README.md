# ServiceNow-Based Car Rental Request Application

## About the Project

The **ServiceNow-Based Car Rental Request Application** automates company car requests, approvals, fulfilment tasks, email notifications, and incident creation using **ServiceNow**.

## Features

- Car rental request form in the Service Catalog
- Approval workflow
- Automatic catalog task for the Transport Team
- Email notification on approval
- Automatic incident creation when a car is unavailable
- Reduced manual intervention

## Technologies Used

### Platform
- **ServiceNow**

### User Interface
- **Service Catalog**

### Application Components
- **Flow Designer**
- **Catalog Variables**
- **Business Rule**

### Notifications
- **ServiceNow Email Notifications**

## Project Workflow

**Employee submits car rental request**  
↓  
**Request Item created**  
↓  
**Approval triggered**  
↓  
**Approver approves the request**  
↓  
**Catalog task assigned to Transport Team**  
↓  
**Approval email sent**  
↓  
**If car is unavailable (Closed Incomplete), incident is created automatically**

## Implementation

1. Create the Car Rental Request catalog item.
2. Add catalog variables: Requestor, Requested Date, Pickup Location, Drop Location, Duration, Car Type, Reason.
3. Design the flow in Flow Designer with the Service Catalog trigger.
4. Add the Ask For Approval action.
5. On approval, create a Catalog Task for the Transport Team.
6. Send an approval email to the requester.
7. Create a Business Rule on the Requested Item table to raise an incident when the car is unavailable.
8. Test the complete lifecycle.

## Project Demo

▶ **Demo Video:** https://drive.google.com/file/d/1zAkOKnPcESWP20k1wrKBXlANzcCcLE_p/view?usp=drivesdk

## Project Details

**Project Name:** ServiceNow-Based Car Rental Request Application

**Team ID:** SWUID2026190369

**Date:** 21/09/2026

## Author

**PACHIGOLLA RUPA SRI MALLESWARI**

B.Tech Computer Science and Engineering

Seshadri Rao Gudlavalleru Engineering College

Graduation Year: **2027**

This project was developed as an **academic project** to demonstrate **workflow automation and approval management using the ServiceNow platform**.
