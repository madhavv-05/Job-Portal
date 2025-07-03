
# Job Portal

A universal, inclusive job portal built with Django and Tailwind CSS — designed to help **anyone**, from skilled professionals to daily-wage workers, find and apply for jobs with ease. The platform removes complexity from the hiring process and makes job discovery and job posting accessible to all.

---

## 🌍 Vision

Most job platforms cater primarily to white-collar sectors. This platform breaks that boundary — connecting local employers with all types of job seekers including laborers, delivery workers, helpers, and skilled professionals. With a minimal UI and quick onboarding, it’s accessible to users regardless of their digital experience.

---

## 🚀 Features

- **Universal Access**  
  Open to everyone — from factory workers to software engineers — without friction.

- **Role-Based Sign Up**  
  Choose between employer or job seeker during registration.

- **Quick Job Posting**  
  Post jobs in under a minute using minimal required fields.

- **Fast Search & Apply**  
  Browse and apply to jobs without complex filters or steps.

- **Application Tracking**  
  Track jobs posted or applied for in a clean dashboard.

- **Video Calling Support**  
  Employers and seekers can schedule remote interview calls.

- **Security & Validation**  
  Secure session handling, form validation, and clean access control.

- **Mobile-Friendly UI**  
  Designed with Tailwind CSS to work on all screen sizes.

---

## 💡 Future Enhancements

- Multi-language support (Hindi, Tamil, Bengali, etc.)
- WhatsApp-based job interaction & chatbot
- Resume generator for non-technical job seekers
- GPS-based local job matching
- Admin panel for category control and user verification

---

## 🛠️ Tech Stack

| Layer       | Tools/Frameworks               |
|-------------|--------------------------------|
| **Backend** | Django                         |
| **Frontend**| Tailwind CSS, Alpine.js        |
| **Database**| SQLite (default, configurable) |
| **Icons**   | Font Awesome                   |

---

## ⚙️ Installation & Setup

```bash
# 1. Clone the Repository
git clone https://github.com/madhavv-05/Job-Portal.git
cd Job-Portal

# 2. Create & Activate a Virtual Environment
python -m venv venv
source venv/bin/activate        # Linux/macOS
venv\Scripts\activate         # Windows

# 3. Install Dependencies
pip install -r requirements.txt

# 4. Apply Migrations
python manage.py migrate

# 5. Run the Server
python manage.py runserver
```

Visit: `http://127.0.0.1:8000/`

---

## 👥 Usage

- **Job Seekers**:  
  Sign up, browse local jobs, apply with one click, and track responses.

- **Employers**:  
  Register quickly, post job listings, and manage applications efficiently.

---

## 📸 Screenshots

Below are some screenshots of the platform in action:

![Job Listings](https://github.com/user-attachments/assets/989e336a-d8e8-4054-91cd-ec100af51b57)
![Job Posting](https://github.com/user-attachments/assets/5b075b5b-412b-4888-97fd-50479a3f4e52)
![Employer Dashboard](https://github.com/user-attachments/assets/69b9a5f4-0485-4708-b488-27d91372453b)
![Login Page](https://github.com/user-attachments/assets/9a40dc07-147d-4d08-8650-396e83a1e528)
![Signup Selection](https://github.com/user-attachments/assets/a29a0093-ed80-4e23-ad3a-2567cbfe2646)
![Jobseeker Signup](https://github.com/user-attachments/assets/c50dca25-56af-4953-a375-e429a3586f27)
![Employer Signup](https://github.com/user-attachments/assets/eab4b12f-6306-44bb-936e-bbe4856ea6ce)
![Job Detail Page](https://github.com/user-attachments/assets/8118b19a-8352-4a86-b073-1de29f2b1359)
![Homepage](https://github.com/user-attachments/assets/ee6ea4c3-c0c9-43be-9bd3-36cc8db4da27)
![Companies List](https://github.com/user-attachments/assets/5b8c71ed-ba44-48e4-9ba9-7bcd06ae1777)
![Company Detail](https://github.com/user-attachments/assets/bde2d5dc-6a2a-4087-933a-c4031d02c22a)

---

### 📌 How to Show Images in README on GitHub

To show screenshots in a GitHub `README.md`, use this Markdown syntax:

```markdown
![Alt Text](relative/or/full/image/path.png)
```

For example, if your image is in the `assets/` folder:

```markdown
![Home Page](assets/homepage.png)
```

Or if it’s a full GitHub image URL:

```markdown
![Job Posting](https://github.com/username/repo/blob/main/assets/job-posting.png?raw=true)
```

✅ **Tip**: Always use `?raw=true` at the end of the GitHub image URL to display the image correctly in markdown.

---

## 🤝 Contributing

Contributions are welcome and appreciated! To contribute:

1. Fork the repository  
2. Create a new branch: `git checkout -b feature/your-feature-name`  
3. Commit your changes  
4. Push to your fork  
5. Open a pull request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Django and Tailwind CSS communities for their excellent tools and documentation  
- Font Awesome for scalable, open-source icons  
- Open-source contributors and testers who improve the platform

---

> Built to simplify hiring, reduce barriers, and open job access to everyone — not just those with resumes or degrees.
