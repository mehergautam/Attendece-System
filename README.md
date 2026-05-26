<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=2ab5a0&height=200&section=header&text=MSCIT%20Attendance&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Smart%20Self-Attendance%20System%20for%20Computer%20Centers&descAlignY=60&descColor=e0fdf4" width="100%"/>

<br/>

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Visit%20Now-2ab5a0?style=for-the-badge)](https://mehergautam.github.io/Attendece-System/portal.html)
[![GitHub](https://img.shields.io/badge/GitHub-mehergautam-091e42?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mehergautam/Attendece-System)
[![Made in India](https://img.shields.io/badge/Made%20with%20❤️%20in-India-FF9933?style=for-the-badge)](https://github.com/mehergautam/Attendece-System)
[![MIT License](https://img.shields.io/badge/License-MIT-2ab5a0?style=for-the-badge)](LICENSE)

<br/>

> ### 🎓 Zero Hardware · Zero Headache · 100% Automatic
> *Students mark their own attendance — you just watch the dashboard*

<br/>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=github&logoColor=white)

</div>

---

## 🚨 The Problem

Running an MSCIT center means dealing with:

- 📋 Manual attendance registers — time consuming & error prone
- 👨‍🏫 Teacher dependency — absent teacher = no attendance
- 📊 No real-time reports — monthly calculations are a nightmare
- 🕐 Flexible timing centers — no fixed batch = no system works

**Every existing solution needs hardware, server, or monthly fees.**

---

## ✅ The Solution — Minute Self Attendance

```
Student arrives at center
        ↓
Opens padmashricomputer.org/attendance
        ↓
Logs in with Roll Number + Password
        ↓
Clicks "Start Session" → Timer begins
        ↓
Works on PC for 30 minutes
        ↓
🎉 POPUP: "Attendance Marked! Click OK"
        ↓
Admin sees it instantly on dashboard
```

**Zero involvement from you. Zero hardware. Zero cost.**

---

## ⚡ Features

<div align="center">

| Feature | Details |
|:--------|:--------|
| ⏱️ Auto Timer | 30-min countdown — attendance marks itself |
| 🔔 Smart Popup | Appears on top of everything after 30 min |
| 📊 Admin Dashboard | Real-time attendance, reports, student management |
| 👨‍🎓 Student Portal | Clean login, timer, history — works on any device |
| 📈 Reports & Export | Download attendance as CSV anytime |
| 🗂️ Batch Archive | Clear old batch data, fresh start for new batch |
| ☁️ Cloud Database | Supabase — data safe even if PC crashes |
| 📱 Mobile Friendly | Works on phone, tablet, laptop — any screen |
| 🔒 Secure Login | Roll number + password — no proxy possible |
| 💰 100% Free | GitHub Pages + Supabase free tier — ₹0/month |

</div>

---

## 🏗️ Tech Stack

<div align="center">

```
┌─────────────────────────────────────────────┐
│              FRONTEND                       │
│   HTML · CSS · Vanilla JavaScript           │
│   Hosted on GitHub Pages — FREE             │
├─────────────────────────────────────────────┤
│              DATABASE                       │
│   Supabase (PostgreSQL) — FREE              │
│   Cloud hosted · Auto backup · Secure       │
├─────────────────────────────────────────────┤
│              DESIGN                         │
│   Plus Jakarta Sans · DM Sans               │
│   Green theme matching center branding      │
└─────────────────────────────────────────────┘
```

</div>

---

## 📁 File Structure

```
Attendece-System/
├── portal.html      ← Landing page (Student / Admin choice)
├── index.html       ← Student portal (Login + Timer + Popup)
├── admin.html       ← Admin dashboard (Reports + Management)
└── config.js        ← Supabase connection settings
```

---

## 🚀 Quick Setup for New Center

**Step 1 — Supabase Setup**
```
1. Go to supabase.com → Create free account
2. New project → Run the SQL setup script
3. Copy Project URL + Publishable Key
```

**Step 2 — Update config.js**
```js
const SUPABASE_URL = 'your_project_url';
const SUPABASE_KEY = 'your_publishable_key';
const SESSION_DURATION_MINUTES = 30;
const CENTER_NAME = 'Your Center Name';
```

**Step 3 — Deploy**
```
Upload files to GitHub → Enable GitHub Pages → Done!
```

**Step 4 — Add Students**
```
Open admin.html → Login → Students tab → Add Student
Set Roll Number + Password → Student can login instantly
```

---

## 👤 Login Credentials

| Role | Field | Example |
|:-----|:------|:--------|
| Student | Roll Number | `MSCIT001` |
| Student | Password | Set by admin |
| Admin | Email | `admin@yourcenter.com` |
| Admin | Password | Set during setup |

---

## 📊 Admin Dashboard Features

<details>
<summary><b>📋 Overview — Today's attendance at a glance</b></summary>
<br/>

- Total students present vs absent today
- Low attendance alerts (below 75%)
- Real-time updates — no refresh needed

</details>

<details>
<summary><b>👨‍🎓 Students — Manage all students</b></summary>
<br/>

- Add new students with roll number + password
- Search & filter students
- Remove students when they leave

</details>

<details>
<summary><b>📅 Attendance — Date-wise records</b></summary>
<br/>

- Filter by any date
- See exact time each student marked attendance
- Present / Absent status clearly shown

</details>

<details>
<summary><b>📈 Reports — Export anytime</b></summary>
<br/>

- Student-wise attendance percentage
- Progress bars for visual summary
- Download as CSV — share with anyone

</details>

<details>
<summary><b>🗂️ Settings — Batch management</b></summary>
<br/>

- Archive old batch → Export report → Clear data
- Fresh start for new batch
- Database stays free forever

</details>

---

## 💰 Cost Breakdown

<div align="center">

| Service | Free Limit | Your Usage | Cost |
|:--------|:----------:|:----------:|:----:|
| GitHub Pages | Unlimited | Static hosting | ₹0 |
| Supabase DB | 500 MB | ~6 MB / 100 students / year | ₹0 |
| Supabase API | Unlimited requests | Normal usage | ₹0 |
| Custom Domain | — | Optional | Optional |
| **Total** | | | **₹0/month** |

</div>

---

## 🗺️ Roadmap

```
✅ Phase 1 — Core System (DONE)
   ├── Student self-attendance with 30-min timer
   ├── Auto popup on completion
   ├── Admin dashboard with real-time data
   ├── Student management (add/remove)
   ├── Date-wise attendance records
   ├── CSV export & batch archive
   └── Mobile responsive design

🔄 Phase 2 — Coming Soon
   ├── Face Recognition (browser-based, no hardware)
   ├── SMS/WhatsApp alert for low attendance
   ├── Monthly PDF report generation
   └── Multi-center Super Admin panel

🔮 Phase 3 — Future
   ├── Mobile App (PWA)
   ├── Biometric integration (optional)
   └── Parent portal for attendance tracking
```

---

## 🤝 SaaS Ready

This system is built to sell to multiple MSCIT centers:

- Each center gets their own Supabase database
- Same codebase — just change `config.js`
- Zero recurring cost for you or the center
- One-time setup fee model

---

## 👨‍💻 Author

<div align="center">

<img src="https://github.com/mehergautam.png" width="100px" style="border-radius:50%"/>

### Meher Gautam
*CSE Student · Full Stack Developer · Builder*

[![GitHub](https://img.shields.io/badge/GitHub-mehergautam-091e42?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mehergautam)
[![Live Project](https://img.shields.io/badge/🚀%20Live-Attendance%20Portal-2ab5a0?style=for-the-badge)](https://mehergautam.github.io/Attendece-System/portal.html)

<br/>

> *"Built for Padmashri Computer Center, Amravati —*
> *because attendance should be automatic, not a headache."*

</div>

---

<div align="center">

**📄 MIT License** · Built for MSCIT Centers across Maharashtra

<img src="https://capsule-render.vercel.app/api?type=waving&color=2ab5a0&height=120&section=footer&text=Zero%20Hardware.%20Zero%20Cost.%20100%25%20Automatic.&fontSize=22&fontColor=ffffff&animation=fadeIn" width="100%"/>

</div>
