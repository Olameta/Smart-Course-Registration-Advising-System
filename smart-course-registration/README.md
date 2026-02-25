# 🎓 Smart Course Registration & Advising System

A digital management platform designed to automate university course enrollment and academic advising. This system eliminates manual enrollment errors by enforcing Role-Based Access Control (RBAC) and automated prerequisite validation.

## 🚀 Features
- **Role-Based Access:** Distinct dashboards and permissions for Students and Advisors. 
- **Smart Prerequisite Logic:** Prevents students from enrolling in advanced courses until foundational units are "Approved." 
- **Real-time Status Tracking:** Students can view their registration status (Pending/Approved) in real-time. 
- **Advisor Tools:** Advisors can manage the course catalog and review/approve student registration requests. 

## 🛠 Tech Stack
| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Interface** | Gradio | Web-based dashboard & UI components |
| **Database** | SQLite3 | Relational storage for users, courses, and logs |
| **Logic** | Python 3 | Session management and prerequisite validation |
| **Environment**| Google Colab | Execution environment and public URL hosting |

## 📦 Installation & Setup

### Prerequisites
- Python 3.7+
- A Google Colab account (recommended) or a local Python environment.

### Local Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/smart-course-system.git](https://github.com/yourusername/smart-course-system.git)
2. Install dependencies:
pip install gradio

3. Run the application:
python course_registration_and_advisor_system.py

### 🖥 Usage Example
Advisor: Log in to add a course (e.g., CSC101). Then add CSC201 with CSC101 listed as the prerequisite. 

Student: Register for CSC201. The system will block the request until you have registered and been approved for CSC101.
   cd smart-course-system
### 📄 License
This project is licensed under the MIT License

### Project Structure
Plaintext

├── course_registration_and_advisor_system.py  # Main application logic and Gradio UI 
├── Group 6 report.pdf                        # Project documentation and methodology
├── UML diagram/                              # Visual system architecture
│   ├── class diagram.png                     # Data model and relationships 
│   ├── Sequence diagram.png                  # Logic flow for prerequisite checks 
│   └── use case diagram.png                  # User interaction boundaries
└── README.md                                 # Project overview and setup instruct
