
# Hospital Platform

## Overview
The Hospital Platform is a user-friendly web application designed for seamless healthcare management. It serves as a centralized hub for patients and hospitals, enabling users to schedule appointments, receive prescriptions, and access essential health features. The platform also supports various health functionalities, such as vitals tracking, BMI calculation, and breathing exercises for enhanced lung capacity. Additional features include a blood donation management system and resources for mental health awareness.
![097ecf30dfa091cbe70af32cbaa2296755797e7f 1](https://github.com/user-attachments/assets/bf58ff95-d40e-4d71-9969-7784f6f988e9)


## Key Features
- **Appointment Booking**: Patients can book appointments with doctors, and doctors can provide prescriptions directly on the platform.
  ![IMG-20241030-WA0028 1](https://github.com/user-attachments/assets/f29abb45-bbad-405f-ba01-25f07eb39ac0)

- **Digital Prescriptions**: Users can access digital copies of prescriptions issued by doctors.
  ![IMG-20241030-WA0031 1](https://github.com/user-attachments/assets/6154773d-9b1f-4422-ab46-f96fe8c507f6)

- **Health Monitoring**:
  - Track vitals such as blood pressure, heart rate, and more.
  - Calculate BMI based on user inputs.
  - Guided breathing exercises to improve lung capacity.
  ![IMG-20241030-WA0030 1](https://github.com/user-attachments/assets/7517a522-28a8-43a5-8e0f-ca23185e0ede)

- **Blood Donation**: Users can register as donors, check donor availability, and access blood donation records.
  ![IMG-20241030-WA0029 1](https://github.com/user-attachments/assets/d4306c66-794d-4349-8d4a-9d45ed60debb)

- **Mental Health Awareness**: Access resources and information to support mental health.

## Technology Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: phpMyAdmin with XAMPP (MySQL)

## Setup Instructions

### 1. Install XAMPP
   - Download XAMPP to your desktop and install it.
   - Open the XAMPP Control Panel.
   - Start the following services:
     - **Apache**
     - **MySQL**
       ![image](https://github.com/user-attachments/assets/c59b1d0c-0a8f-4bdf-829e-65988fcae68d)


### 2. Access phpMyAdmin
   - Open a web browser.
   - Go to `localhost` in the address bar.
   - From the XAMPP dashboard, open **phpMyAdmin**.
     ![IMG-20241030-WA0032 1](https://github.com/user-attachments/assets/1de74211-8146-4c4e-b738-bfa791091c64)


### 3. Create the Database
   - In phpMyAdmin, create a new database named `hospital_platform`.
   - This database will store essential information such as patient details, doctor records, appointment data, and prescription logs.

### 4. Set Up Database Tables
   - Inside the `hospital_platform` database, create tables to support the platform’s functionalities:
     - **Patients**: Store patient details (e.g., name, age, contact info).
     - **Doctors**: Store doctor profiles and specialties.
     - **Appointments**: Manage appointment bookings between patients and doctors.
     - **Prescriptions**: Store prescription records associated with patient profiles.
     - **Vitals**: Store health data, such as blood pressure and BMI measurements.
     - **Blood_Donors**: Register blood donor details and availability status.

### 5. Connect the Platform to the Database
   - Configure database connection settings in the platform’s backend PHP files to enable data access and storage.
   - Verify connections to ensure that data entries (such as user registration, appointments, and prescriptions) are stored accurately in phpMyAdmin.

## Usage
1. **User Registration**: New users can register with their details to create a profile.
2. **Book Appointment**: Patients can schedule appointments with available doctors.
3. **Vitals Monitoring**: Track personal health metrics, calculate BMI, and perform breathing exercises.
4. **Blood Donation**: Check availability of blood donors or register to donate blood.
5. **Mental Health Resources**: Access helpful resources for mental health awareness and support.

## Additional Information
This project is developed using **PHP** and **phpMyAdmin**, and it requires **XAMPP** to run locally. Please ensure that XAMPP is correctly configured as detailed above.

## Contributing
Contributions are welcome! Please submit a pull request for any features or improvements.

## License
This project is open-source and available under the [MIT License](LICENSE).
