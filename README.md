# Salesforce Car Rental CRM

This project is a Salesforce-based Car Rental CRM built using declarative tools.

The system manages cars and rental bookings and automates the complete rental approval workflow.

## Key Features
- Custom objects for Car and Rental Booking
- Auto-calculated rental amount based on duration and daily rate
- Validation to prevent incorrect booking dates
- Approval process for high-value rentals
- Salesforce Flow to automatically update car status after approval

## Workflow
1. A car is added with pricing and availability
2. A rental booking is created
3. If the rental amount exceeds a defined threshold, approval is required
4. After approval, the booking is marked approved and the car status is updated automatically

## Tools Used
- Salesforce Custom Objects
- Formula Fields
- Validation Rules
- Approval Process
- Record-Triggered Flow

This project demonstrates how Salesforce can be used to automate real-world business processes without writing Apex code.