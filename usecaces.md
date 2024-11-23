# usecace 1: Add Patient Record
### Use Case ID : UC-001
### Use Case Name: Add patient Record
### Actors: Staff(Primary),Doctor(Secondary)
### Precondition :
(1) The staff or doctor must be logged into
the system.

(2) The patient must provide valid details.
### Basic Flow: 
(1) The actor selects "Add Patient Record"
from the system menu.

(2)The actor enters patient details,
including name, age, contact information,
and medical history.

(3) The actor confirms the details.

(4) The system saves the patient record and
displays a success message.
### Alternative Flows: 
If any mandatory fields are missing, the
system displays an error message and
prompts the actor to complete them.
### Postconditions :
The patient record is stored in the system
and available for future use.

# usecace 2:Schedule Appointment
### Use Case Name :Schedule Appointment
### Use Case ID: UC-002
### Actors: Patient (Primary), Doctor (Secondary)
### Preconditions: 
- The patient must have an account and be
logged into the system.
- Appointment slots must be available.
### Basic Flow: 
(1) The patient selects "Schedule
Appointment" from the dashboard.

(2) The patient chooses a doctor and views
available time slots.

(3) The patient selects a preferred slot and
confirms.

(4) The system notifies the doctor of the
new appointment and updates the
schedule.

### Alternative Flows: 
- If the selected slot is no longer available,
the system prompts the patient to choose
another slot.
### Postconditions: 
The appointment is added to the system
and visible to both the patient and the
doctor.

# Use Case 3: Generate Bill
### Use case : name generate bill
### Use Case ID : UC-003
### Actor: Staff (Primary), Patient (Secondary)
### precondition: 
(1)The patient must have used hospital
services.

(2)Staff must be logged into the system
### Main Flow: 
(1) actor select to generate bill

(2) enter the name of the patient

(3)actor review the data of the patient and
check his services

(4)system calculates the total bill amount

(5)actor print the bill to the patient
### Alternative Flows: 
If the patient ID is invalid, the system
displays an error and prompts for reentry.
### Postcondition :
The bill is generated and available for
printing

# UseCase 4 : Generate Report
### Use case : name generate Report
### Use Case ID: UC-004
### Actor: Doctor (Primary), Admin (Secondary)
### Precondition: 
the patient logged into the system and
has already accounted for and dealt with
this system
### Main flow: 
(1) actor select generate Report

(2) actor selects the patient and makes
sure of data

(3) actor can view, print, or email to the
patient
### Alternative flow: 
If insufficient data exists, the system
alerts the actor and cancels the operation.
### Postconditions: 
The report is generated and accessible to
the actor.

# Use Case5: view patient Medical Data
### Use Case Name: View patient Medical Data
### Use Case ID : UC-005
### Actors: Patient(Primary)
### Precondition: 
The patient already has an account and
logged into the system.
Main flow:
(1) The patient logged into the system

(2) The system verifies the patient's
identity

(3)system appears for the user all the
treatments and next appointments

(4)the patient can view or print data
### Alternative flow: 
if a name or email is already used
system prompts for a different email.
### Postconditions: 
The patient successfully views their
medical data.

# Use Case 6: Manage Doctor Schedule
### Use Case Name : Manage Doctor Schedule
### Use Case ID: UC-006
### Actors: Doctor (Primary)
### Preconditions: 
The doctor must be logged into the
system.
### Basic Flow: 
(1) The doctor selects "Manage Schedule"
from the menu.

(2)The doctor views the current schedule.

(3)Doctor updates or cancels
appointments as needed.

(4)The system notifies affected patients of
the changes.
### Alternative Flows: 
If the doctor tries to cancel a slot that has
a booked appointment, the system
prompts for confirmation.
### Postconditions: 
The updated schedule is saved and
reflected in the system.