
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
![image](https://github.com/user-attachments/assets/b82e4707-d0a2-48cd-8d01-b95e1dc756b3)


![image](https://github.com/user-attachments/assets/91341b56-6a62-45e1-b122-aa5f4ec691d9)
![image](https://github.com/user-attachments/assets/d4a0b152-11f4-4156-bfd7-e8b220d19afb)


![image](https://github.com/user-attachments/assets/3989179e-6ec0-4f92-9fc2-066c4ebffa0b)


### Contact
rk20040211@gmail.com



   
