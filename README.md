
# Job Management Admin Interface

This project is a **Job Management Admin Interface** that allows administrators to create, manage, and filter job postings. It is a full-stack application with:

- **Frontend**: Built using **Mantine**, **Next.js**, and **React Hook Form**.
- **Backend**: Built using **Node.js** and **PostgreSQL**.

The infrastructure includes:
- **Database**: Hosted on **Railway**.
- **Backend**: Hosted on **Render**.
- **Frontend**: Hosted on **Vercel**.

---

## Features

### Frontend
- **Job List Page**:
  - Display a list of job postings.
  - Filters:
    - **Job Title**: Text input.
    - **Location**: Text input.
    - **Job Type**: Dropdown with options: Full-time, Part-time, Contract, Internship.
    - **Salary Range**: Range slider.
- **Job Creation Page**:
  - Form to create a new job posting.
  - **Form Handling**: Uses React Hook Form for efficient form handling and validation.

### Backend
- Built with **Node.js** and **PostgreSQL**.
- Hosted on **Railway**.
- Provides RESTful APIs for managing job data, including job creation, retrieval, updating, and deletion.

---

## Job Fields

### Fields for Job Creation
1. **Job Title**: Text input for the job's title.
2. **Company Name**: Text input for the company's name.
3. **Location**: Text input for the job's location.
4. **Job Type**: Dropdown with options:
   - Full-time
   - Part-time
   - Contract
   - Internship
5. **Salary Range**: Text input to specify the salary range.
6. **Job Description**: Textarea for describing the job role.
7. **Requirements**: Textarea to list job requirements.
8. **Responsibilities**: Textarea to outline the job's responsibilities.
9. **Application Deadline**: Date picker to specify the deadline for job applications.

### Components for Filters
- **Job Title**: Text input for filtering jobs by title.
- **Location**: Text input for filtering jobs by location.
- **Job Type**: Dropdown for filtering by job type.
- **Salary Range**: Range slider for filtering jobs by salary.

---

## Tech Stack

### Frontend
- **Framework**: Next.js
- **UI Library**: Mantine
- **Form Handling**: React Hook Form
- **Language**: TypeScript

### Backend
- **Framework**: Node.js
- **Database**: PostgreSQL (hosted on Railway)
- **Hosting**: Railway

---

## Installation and Setup

### Prerequisites
- Node.js (v16+)
- PostgreSQL
- Railway account for backend hosting
- Yarn or npm installed globally

### Backend Setup
1. Clone the backend repository:
   ```bash
   git clone <backend-repo-url>
   cd backend
   ```
2. Install dependencies:
  ```bash
npm install.
```

3. Set up environment variables: Create a .env file in the backend directory with the following:
   ```bash
   DATABASE_URL=<Your PostgreSQL connection string>.

4.Run the backend server:
```bash
npm run dev
```
5.The backend server will be available at http://localhost:8000.

### Frontend Setup
1. Clone the frontend repository:
   ```bash
   git clone <frontend-repo-url>
   cd cybermindworks_frontend
   ```
2. Install dependencies:
  ```bash
npm install.
```

3. Configure environment variables: Create a .env.local file in the frontend directory with:
   ```bash
   NEXT_PUBLIC_API_URL=http://localhost:3000.

4.Run the server:
```bash
npm run dev
```
5. Access the frontend at http://localhost:3000..

### API Endpoints
**Jobs**
   - GET /api/jobs: Fetch all jobs.
   - POST /api/jobs: Add a new job.

     
### Screenshots
![Screenshot 2024-12-26 114019](https://github.com/user-attachments/assets/bcc2002f-e161-4978-8a44-f16c941fdfb4)

![image](https://github.com/user-attachments/assets/7044b217-a8e9-48af-84e0-d3a99758f665)
![Screenshot 2024-12-26 114035](https://github.com/user-attachments/assets/4a3a504d-c61d-483f-b00e-ca9780670057)

### Contact
rk20040211@gmail.com



   
