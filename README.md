
# CarePluse — A healthcare patient management application 
<img width="959" alt="Screenshot 2024-07-27 162149" src="https://github.com/user-attachments/assets/a1c9b659-95ed-461c-9c9f-19b0d7bda0c1">

A healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors, featuring administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications, all built using Next.js.




## Features
👉 Register as a Patient: Users can sign up and create a personal profile as a patient.
<img width="959" alt="Screenshot 2024-07-27 215842" src="https://github.com/user-attachments/assets/23105ea2-ee90-4a3b-ad60-c6a381761639">
<img width="959" alt="Screenshot 2024-07-27 220035" src="https://github.com/user-attachments/assets/b0cbc852-993f-4c21-805b-21e27f0dabf8">
<img width="959" alt="Screenshot 2024-07-27 220231" src="https://github.com/user-attachments/assets/7f67fab9-791a-4c42-8660-a5e2adde67a7">

👉 Book a New Appointment with Doctor: Patients can schedule appointments with doctors at their convenience and can book multiple appointments.
<img width="959" alt="Screenshot 2024-07-27 220500" src="https://github.com/user-attachments/assets/1843b59a-ecf0-4a5f-85b3-98196149ddbc">

👉 Manage Appointments on Admin Side: Administrators can efficiently view and handle all scheduled appointments.
<img width="959" alt="Screenshot 2024-07-27 220642" src="https://github.com/user-attachments/assets/4e0a9211-08de-49e1-a46d-fafcbc1955ac">

👉 Confirm/Schedule Appointment from Admin Side: Admins can confirm and set appointment times to ensure they are properly scheduled.

👉 Cancel Appointment from Admin Side: Administrators have the ability to cancel any appointment as needed.

<img width="959" alt="Screenshot 2024-07-27 220845" src="https://github.com/user-attachments/assets/7175ccd7-5c11-45fb-a44c-1de5491b0a66">
<img width="955" alt="Screenshot 2024-07-27 220941" src="https://github.com/user-attachments/assets/6c262cae-188a-45e6-935d-490fbea97f25">

👉 Send SMS on Appointment Confirmation: Patients receive SMS notifications to confirm their appointment details.

👉 Complete Responsiveness: The application works seamlessly on all device types and screen sizes.

👉 File Upload Using Appwrite Storage: Users can upload and store files securely within the app using Appwrite storage services.

👉 Manage and Track Application Performance Using Sentry: The application uses Sentry to monitor and track its performance and detect any errors.


## Tech Stack
- Next.js
- Appwrite
- Typescript
- TailwindCSS
- ShadCN
- Twilio

## Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/manojku1803/CarePluse_PatientsHealthCareSystem
cd healthcare
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
