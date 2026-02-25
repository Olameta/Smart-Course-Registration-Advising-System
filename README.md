# 🎓 Smart Course Registration & Advising System

A digital management platform designed to automate university course enrollment and academic advising. This system eliminates manual enrollment errors by enforcing Role-Based Access Control (RBAC) and automated prerequisite validation.

## 🚀 Features
- **Role-Based Access:** Distinct dashboards and permissions for Students and Advisors. [cite: 31]
- **Smart Prerequisite Logic:** Prevents students from enrolling in advanced courses until foundational units are "Approved." [cite: 31, 87]
- **Real-time Status Tracking:** Students can view their registration status (Pending/Approved) in real-time. [cite: 33, 43]
- **Advisor Tools:** Advisors can manage the course catalog and review/approve student registration requests. [cite: 90, 105]

## 🛠 Tech Stack
| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Interface** | Gradio | [cite_start]Web-based dashboard & UI components [cite: 37] |
| **Database** | SQLite3 | [cite_start]Relational storage for users, courses, and logs [cite: 37] |
| **Logic** | Python 3 | [cite_start]Session management and prerequisite validation [cite: 37] |
| **Environment**| Google Colab | [cite_start]Execution environment and public URL hosting [cite: 37] |

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
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.


---

### .gitignore
```ignore
# Byte-compiled / optimized / DLL files
__pycache__/
*.py[cod]
*$py.class

# Database
course_system.db

# OS-specific files
.DS_Store
Thumbs.db

# Virtual environments
venv/
env/
.env

# Colab / Jupyter notebooks
.ipynb_checkpoints/
Project Structure
Plaintext
.
├── course_registration_and_advisor_system.py  # Main application logic and Gradio UI [cite: 36]
├── Group 6 report.pdf                        # Project documentation and methodology [cite: 1]
├── UML diagram/                              # Visual system architecture
│   ├── class diagram.png                     # Data model and relationships [cite: 113]
│   ├── Sequence diagram.png                  # Logic flow for prerequisite checks [cite: 115]
│   └── use case diagram.png                  # User interaction boundaries [cite: 111]
└── README.md                                 # Project overview and setup instruct
