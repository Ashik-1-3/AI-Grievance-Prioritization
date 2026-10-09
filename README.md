# AI-Powered Grievance Prioritization System

An AI-powered grievance management platform designed to simplify citizen complaint handling by analyzing grievances, identifying urgency, detecting duplicate complaints, and helping administrators manage issues more efficiently.

## 📌 About the Project

Government departments and public service organizations receive a large number of complaints every day. Manually reviewing and prioritizing every grievance can delay responses to urgent problems and make it difficult to identify recurring issues.

The **AI-Powered Grievance Prioritization System** aims to improve this process using Artificial Intelligence (AI), Natural Language Processing (NLP), and a user-friendly web interface.

## 🎯 Objectives

- Automate grievance categorization and priority assessment.
- Identify duplicate or similar complaints.
- Analyze complaint sentiment.
- Help citizens submit and track grievances.
- Support administrators in monitoring complaints and updating their status.
- Provide relevant department and helpline information based on location.

## ✨ Key Features

- **Grievance Submission:** Submit complaints through a web interface.
- **AI-Based Categorization:** Categorize complaints based on their descriptions.
- **Priority Assessment:** Identify the urgency of submitted grievances.
- **Duplicate Detection:** Check whether a complaint may already exist.
- **Sentiment Analysis:** Analyze the tone of grievance descriptions.
- **Grievance Tracking:** Generate a tracking ID for submitted complaints.
- **Admin Dashboard:** View grievances and manage their status.
- **Officer Assignment:** Assign grievances to responsible officers.
- **Location-Based Assistance:** Display relevant department, office, and helpline information.
- **Analytics and Reports:** Support grievance monitoring and administrative review.
- **Citizen Feedback:** Collect ratings and feedback on grievances.

## 🛠️ Technologies Used

### Frontend
- React.js
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Recharts
- Lucide React

### Backend
- Python
- FastAPI
- Pydantic

### AI and NLP
- Natural Language Processing (NLP)
- TF-IDF text vectorization
- Machine learning classification techniques
- Naive Bayes and Logistic Regression
- Rule-based priority assessment
- Sentiment analysis
- Duplicate grievance detection

### Data Storage
- JSON-based grievance storage

## ⚙️ System Workflow

1. A citizen submits a grievance through the web application.
2. The backend receives and processes the complaint.
3. AI/NLP modules analyze the description to determine its category, priority, and sentiment.
4. The system checks for duplicate complaints.
5. A unique tracking ID is generated for an accepted grievance.
6. Grievance information is stored for later retrieval.
7. Administrators can review complaints, assign officers, and update statuses.
8. Citizens can use their tracking ID to check grievance progress.

## 🚀 Getting Started

### Prerequisites

Install the following software:

- Node.js and npm
- Python 3.10 or a compatible version
- pip

### 1. Run the Frontend

Open a terminal in the project root directory.

Install the required packages:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL displayed in your terminal, usually `http://localhost:5173`.

### 2. Run the Backend

Open a separate terminal in the project root directory.

Install the backend dependencies:

```bash
pip install fastapi uvicorn pydantic pandas scikit-learn
```

Start the FastAPI server:

```bash
python -m uvicorn api.main:app --reload
```

The backend will normally be available at `http://127.0.0.1:8000`.

To explore the API endpoints, open:

`http://127.0.0.1:8000/docs`

**Note:** Run these commands from the project root, where the `api` and `src` folders are located. Additional dependencies or configuration may be required depending on the installed code and environment.

## 🔮 Future Enhancements

- Multilingual grievance submission and processing.
- Integration with advanced transformer-based NLP models.
- Real-time notifications for high-priority complaints.
- Improved duplicate detection using semantic similarity.
- Secure authentication and role-based access control.
- Cloud deployment and scalable database integration.
- Advanced analytics for identifying regional complaint trends.

## 🌍 Impact

The project explores how AI can support more transparent, organized, and responsive grievance management by helping administrators identify urgent complaints and recurring public issues.

## 👨‍💻 Author

**Mohammad Ashik Shaik**

GitHub: [Ashik-1-3](https://github.com/Ashik-1-3)

---

*Developed as an AI-powered solution for smarter and more efficient grievance management.*

## 📂 Dataset

The dataset used for this project is available on Google Drive.

🔗 **[Access the Dataset](https://drive.google.com/drive/folders/1ZLtPl29TGnc-yyt_WqqG7NRFn7BWd5ih?usp=sharing)**

The dataset supports the development and testing of the AI-powered grievance prioritization system.

**Note:** Ensure that the Google Drive folder has the appropriate sharing permissions so that users can access the dataset.
