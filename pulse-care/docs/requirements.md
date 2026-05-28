            //FUNCTIONAL-REQUIREMENTS:
Pulse care system is designed to perform the following purpose:

        1. AUTHENTICATION MODULE.
=>users login using credentials
=>users credentials are verified
=> users routed to their respective pages.

        2. DATA ENTRY MODULE.
=>receptionists can enter patients data
=>doctors can enter patients diagnosis and pharmaceutical prescriptions.
=>patients can enter their data.
=>CRUD operations can be performed on all data.

     3. EXPERT SYSTEM
=>doctors can record data on predescribed illnesses.
=>the system should be reliable with a 98% accuracy.
=>the system is accessible to the patients but only for consoltation.

        4. BILLING
=>timely handling of payments
=>prevent overloads when transactions are made in bulk.

     5. PATIENT MANAGEMENT
=>handle records of all patients whether inpatieint, outpatient.
=>patient records can be traced and updated.

        6. REPORTS 
=>generate reports for payments made, patient records and prescriptions, staff records.

        7. STAFF COORDINATION
=>staff records are maintained in storage
=>staff login.
        8. APPOINTMENT BOOKING
=>handle appointment allocations and ensure there non conflicting appointments.
=>appointments made by receptionists, doctors.

        9. REFERAL SYSTEM
=>patients can be reffered to partner hospitals, public hospitals and private hospitals and ensure patient records can be accesible to the hospitals.
=>patients referred to the hospitals are preceded by their records.

        10. TICKETING SYSTEM
=>incoming patients are guided by tickets that appeaar at the receptionsts counter through the system, enablinng systematic guding of patient flow and reference.
        11. DATA BACKUP

=>the system will have uptodate data backups for both patient, staff records and the expert system knowledge to prevent data loss.
        12. 

            //NON-FUNCTIONAL REQUIREMENTS:
Pulse care system behaves in the following ways:
        1. SECURITY
=>passwords must be hashed.
=>user session logging is done upon login.
        2. UPTIME
=>An uptime of 24/7, system failure does not render inoperability.
        3. DATA RETENTION AND PROTECTION
=>since the data collected is personal it is kept under tight security and accessed only by authorised personel and used in accordance with the data regulations act.
        4. MAINTENABILITY
=>the system receives updates and does not render operations.
        5. ACCESABILITY
=>the system requires internet connection for external services but performs both offline and online for internal use by hospitals.
        6. DATA RETRIEVAL
=>data requests are handled at a rate of (<2seconds) when load is low and when load is high (2seconds<5seconds.)
        7. USER EXPERIENCE
=>the user interface should be easy to use and not overly complex.
        8.ERROR HANDLING
=>the system has fallback mechanisms to prevent inoperability of the system when unplanned errors occur such as data breach, malware and cyber attacks.
        9. 

            //SYSTEM CONSTRAINTS.
This system although being large and handling large volume data sets has the following constraints:
        1. The system is currently limited to one hospital with plans to expand.
        2. The system is prone to attacks triggered by inexperienced users or attacks.
        3. The system isnt capable of handling very large volumes of data.
        4. Lack of an ai companion to assists users of the system.
        5. Dependance on third party softwares will limit the systems functionality.ie cloud storage .
            //FUTURE-ENHANCEMENTS.
The following enhancements will bring out the fullest potential of the system:
        1.Introduction of an ai model integrated into the system.
        2.Multiple brach support.
        3.Integration into thee government health system.
        4.Mobile app
        5.Video consultation capabilities.

            //USER STORIES.
=>As a patient, i want to consult a doctor remotely
=>As a patient , i want to book an appointment to a doctor.
=>As a patient, i want to view past records of my medications and treatment
=>As a patient, i want my records to be accessed by another hospital.
=>As a patient, i want payments to be made seamlessly with little delay.
=>As a doctor, i want to access patient records.
=>As a doctor, i want to view my booked appointments and schedules.
=>As a doctor, i want to prescribe medication to my patient
=>As a doctor, i want to consult an expert system when i am conflicted.
=>As a receptionist, i want to book appointments for patients.
=>As a receptionist, i want to handle payments made securely and generate reports.
=>As a pharmacist, i want to view patient medications prescribed.
=>As an admin, i want to view all users logged in the system.
=>As an admin, i am able to view errors that occur and handle them.

            //SYSTEM WORKFLOWS>
Define basic steps on how the system flow is expected to occur.
    1.LOGGIN IN
                (USER ENTERS CREDENTIALS)
                        |
                (USER APPROVAL)
                        |
                (USER ROUTING
                    1.ADMIN
                    2.DOCTOR
                    3.RECEPTIONIST
                    4.PATIENT
                    5.NURSE)
    2.APPOINTMENT BOOKING
                (USER SELECTS DATE AND DOCTOR)
                            |
                        (APPROVAL)
                            |
            (DOCTOR CONFIRMS BOOKING AND USER NOTIFIED)
    3. TREATMENT PROCEDURE & PRESCRIPTION
                (USER IS ALLOCATED DOCTOR THROUGH RECEPTIONIST)
                                |
                    (DOCTOR VERIFIES PATIENT DETAILS)
                                |
                (DOCTOR LISTS SYMPTOMPS IN SYSTYEM AND PRESCRIBES MEDICATION,
                EXPERT SYSTEM ANALYSES SYMPTOMPS AND CROSSCHECKS ACROSS ITS DATABANKS, PROVIDES PRESCRIPTION)
                                |
                (PRESCRIPTION IS SENT TO PHARMACY, DOCTOR IS NOTIFIED, DATA STORED IN SYSTEM)
    4.INTER-HOSPITAL DATA TRANSFER
                (USER ISSUES REQUEST FOR DATA TO BE ACCESSED FROM SEPARATE HOSPITAL)
                                        |
                (SYSTEM CHECKS WHETHER INTENDED RECEPTIEN IS UTILISING THE SYSTEM.)
                                        |
                                    (APPROVAL)
                                        |
                (DATA RECORDS ARE SENT TO RECEPIENT, ANY CHANGES MADE OR ALTRECATIONS REQUIRE APPROVAL AND ARE UPDATED ACROSS BOTH SYSTEMS.)
            
                