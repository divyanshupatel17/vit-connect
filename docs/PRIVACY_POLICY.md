# Privacy Policy

**Last Updated:** Oct 2025

VIT Connect ("the App") is a third-party student companion app for VIT Chennai students. This privacy policy explains what data we collect, how we use it, and your rights.

---

## 1. What Data We Collect

### 1.1 VTOP Credentials
- **Username and Password**: Encrypted (AES-256) and stored locally on your device using Flutter Secure Storage.
- **Purpose**: Authenticate with VTOP servers to fetch your academic data.
- **Storage**: Your device only. Never sent to third-party servers.

### 1.2 Academic Data (Fetched from VTOP)
After successful authentication, the App fetches your academic information in **2 phases**:

**Phase 1 (Essential - 5 steps):**
1. Profile Information (Name, Registration Number, Email, etc.)
2. Current Semester Courses
3. Timetable
4. Attendance Summary
5. Detailed Attendance

**Phase 2 (Background - 9 steps):**
6. Marks & Assessments
7. Grade History
8. Exam Schedule
9. All Semester Marks
10. Previous Semester GPA
11. Faculty & Staff Information
12. Announcements (Spotlight)
13. Fee Receipts
14. Dues Check

- **Purpose**: Display your academic performance, attendance, and schedule within the App.
- **Storage**: Local device database (SQLite) and encrypted storage.
- **Sharing**: Never shared with third parties. The App communicates directly with VTOP.

### 1.3 Community Features Data

#### Cab Share & Lost & Found
- **Data Used**: Your Name and Registration Number (from VTOP profile).
- **Purpose**: Display your identity when you create posts in Cab Share or Lost & Found.
- **Visibility**: Visible to other app users when you create a post.
- **Storage**: Stored in Google Sheets via Google Apps Script API.

#### Faculty Rating
- **Anonymity**: Completely anonymous. No name or registration number is collected or displayed.
- **Purpose**: Allow students to rate faculty anonymously.
- **Storage**: Stored in Google Sheets via Google Apps Script API.

### 1.4 Analytics & Crash Reporting
- **Firebase Analytics**: Collects anonymous usage statistics (screen views, feature usage, app performance).
- **Firebase Crashlytics**: Collects crash reports and diagnostic data to improve app stability.
- **Purpose**: Improve app performance and user experience.
- **Identifiability**: No personally identifiable information is sent. Analytics data is anonymized.

### 1.5 Device Permissions
- **Camera**: Required for scanning QR codes and barcodes (optional feature).
- **Storage**: Required for saving timetable images and lost & found photos.
- **Internet**: Required to communicate with VTOP and Google Sheets APIs.

---

## 2. How We Use Your Data

- **VTOP Authentication**: Your credentials are used solely to log in to VTOP and fetch your academic data.
- **Academic Display**: Fetched academic data is displayed within the App for your personal use.
- **Community Features**: Your name and registration number are displayed only when you create posts in Cab Share or Lost & Found.
- **Analytics**: Anonymous usage data helps us improve the App.
- **No Third-Party Sharing**: Your VTOP credentials and academic data are NEVER shared with any third-party services, advertisers, or external entities.

---

## 3. Data Storage & Security

- **Local Storage**: All VTOP credentials and academic data are stored locally on your device.
- **Encryption**: Credentials are encrypted using AES-256 encryption and stored in Flutter Secure Storage.
- **Cloud Storage**: Community feature posts (Cab Share, Lost & Found, Faculty Rating) are stored in Google Sheets for sharing among users.
- **No Cloud Backup**: Your VTOP credentials and academic data are NOT backed up to any cloud service.

---

## 4. CAPTCHA Solving & Privacy

The App uses a **3-Stage CAPTCHA Pipeline** to solve VTOP login CAPTCHAs:

1. **Stage 1**: Custom Neural Model (>95% accuracy) - runs entirely on your device.
2. **Stage 2**: Google ML Kit OCR (~40% accuracy) - fallback if Stage 1 confidence is <70% - also runs on your device.
3. **Stage 3**: Manual input dialog - you enter the CAPTCHA manually if both models fail.

**Privacy**: All CAPTCHA solving happens locally on your device. No CAPTCHA images or credentials are sent to external servers during this process.

---

## 5. Third-Party Services

### 5.1 VTOP (VIT Official Portal)
- **Purpose**: The App communicates directly with VTOP to authenticate and fetch your academic data.
- **Data Sent**: Your username and password (encrypted in transit via HTTPS).
- **Privacy**: VTOP's own privacy policy applies to data stored on their servers.

### 5.2 Google Sheets (via Google Apps Script API)
- **Purpose**: Store and retrieve community feature posts (Cab Share, Lost & Found, Faculty Rating).
- **Data Sent**: Name, registration number (for Cab Share & Lost & Found ONLY), post content.
- **Privacy**: Google's privacy policy applies to data stored in Google Sheets.

### 5.3 Firebase (Analytics & Crashlytics)
- **Purpose**: Collect anonymous usage statistics and crash reports.
- **Privacy**: Firebase's privacy policy applies. No personally identifiable information is sent.

---

## 6. Your Rights

- **Access**: You can view all your data within the App.
- **Deletion**: You can delete your local data by logging out or uninstalling the App.
- **Community Posts**: You can delete your own posts from Cab Share and Lost & Found within the App.
- **Opt-Out**: You cannot opt out of Firebase Analytics/Crashlytics without uninstalling the App.

---

## 7. Data Retention

- **Local Data**: Academic data is stored on your device until you log out or uninstall the App.
- **Community Posts**: Stored in Google Sheets indefinitely until you delete them.
- **Analytics Data**: Retained by Firebase according to their retention policy.

---

## 8. No Control or Responsibility

VIT Connect is a third-party app developed independently by students. We do **NOT** have any control over:

- VTOP's availability, uptime, or data accuracy.
- VIT Chennai's official policies or academic data.
- Google Sheets API or Firebase service availability.

We are **NOT** responsible for:

- Any data loss, inaccuracies, or issues arising from VTOP servers.
- Any consequences of using community features (Cab Share, Lost & Found, Faculty Rating).
- Any academic or administrative decisions made by VIT Chennai.

**Use the App at your own risk.**


---

## 9. Changes to This Policy

We may update this privacy policy from time to time. Check the "Last Updated" date at the top. Continued use of the App after changes constitutes acceptance.

---

## 10. Contact Us

For questions or concerns about this privacy policy:

- **Email**: itzdivyanshupatel@gmail.com
- **GitHub**: https://github.com/divyanshupatel17/vit-connect

---

**By using VIT Connect, you agree to this Privacy Policy.**
