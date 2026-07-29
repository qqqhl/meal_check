# 🍽️ Yummy Healthy Checker (냠냠 튼튼 점검 대장)

A simple, browser-based web application designed for teachers to track students' healthy eating habits and manage meal-time rewards easily.

## 🚀 Features

- **Class Management:** Easily add, edit, and organize students by grade and class.
- **Daily Attendance/Check:** Track students' eating status using a simple 3-button system:
    - ⭕ (Completed): Excellent!
    - 🔺 (Partial/Try): Good effort!
    - ❌ (Skipped): Needs encouragement.
- **Automatic Calculation:** Automatically calculates the total score based on historical data.
- **Reward System:** Manage and deduct points for rewards directly within the app.
- **Data Persistence:** All data is saved locally in your browser's `localStorage` (no backend required).
- **Lightweight & Fast:** Built with pure HTML, CSS, and JavaScript.

## 🛠️ How to Use

1. **Setup:** On your first visit, add your class name (e.g., 1st Grade 1st Class) and input student names separated by commas or line breaks.
2. **Daily Tracking:** Select the date, choose a class, and click the status buttons for each student.
3. **Reward Management:** View the total accumulated points and click the "Gift (🎁)" button to deduct points when a student receives a reward.
4. **Data Management:** You can edit student rosters at any time or reset all data if necessary.

## 💡 Notes

- **Data Privacy:** This app uses `localStorage`. Your data is stored **only** on the device you are currently using. If you switch devices (e.g., from PC to mobile), the data will not automatically sync.
- **Backup:** Since the data is stored in the browser, clearing your browser cache/history may result in data loss. Please be mindful when cleaning your browser.

## 📝 License

This project is open-source and free to use for educational purposes.

---
*Built with ❤️ for teachers.*
