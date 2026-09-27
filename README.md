🏥 OnKo — Cancer Care Companion

OnKo is a digital companion designed to make cancer care less overwhelming. It brings together patients, doctors, caregivers, and care teams on a single, easy-to-use platform, helping everyone stay connected and informed throughout the entire care journey.

🎯 Goal

We help turn a doctor’s care plan into real, everyday actions that patients and families can follow with confidence.

Doctor → Care Plan → Patient → Activity → Shared Data → AI Insights → Doctor Review

✨ Key Features

👤 Patient Dashboard

* Care journey & timeline
* Medicines and procedures
* Appointments & milestones
* Report uploads
* Doctor queries
* Progress & engagement
* Caregiver coordination
* SOS / escalation

👨‍⚕️ Doctor Dashboard

* Patient management
* Longitudinal history
* Care plans & milestones
* Medicines & procedures
* Report review
* Patient queries
* Progress tracking
* Alerts & engagement signals
* AI-generated summaries

🤖 AI Layer

* Patient history summaries
* Appointment overviews
* Engagement-pattern signals
* Medical knowledge base RAG for doctor reference

AI supports the care team; it does not diagnose, prescribe, modify care plans, or make clinical decisions.

⚙️ Architecture

Patient Dashboard ─┐
                   ├── Backend/API ── Firebase ── Shared Care Data
Doctor Dashboard ──┘                         │
                                             └── AI Layer

Both dashboards use the same underlying patient data to keep care coordination synchronized.

🔐 Security & Privacy

* Role-based access control
* Patient data isolation
* Secure report storage
* Firestore & Storage security rules
* Audit logs
* Environment-based secrets
* No real patient data committed.

🛠️ Tech Stack

Frontend: Next.js, TypeScript, Tailwind CSS
Backend: API services, Firebase
Database: Firestore
Storage: Firebase Storage
AI: Gemini / RAG
Visualization: Recharts
Integration: WhatsApp Business API

👥 Team Structure

Column 1	Column 2
Area	Responsibility
👨‍⚕️ Doctor	Doctor Dashboard
👤 Patient	Patient Dashboard
⚙️ Backend	API, Firebase, AI & Integration


🚀 Core Principle

The patient sees what to do. The doctor sees what needs attention. The backend keeps both synchronized. AI provides supporting insights under human clinical oversight.
