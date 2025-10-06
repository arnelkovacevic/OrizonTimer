# OrizonTimer
🕒 OrizonTimer – Time Tracking Application OrizonTimer is a modern desktop application designed for tracking time and calculating work costs per user — ideal for companies, workshops, salons, coworking spaces, internet cafés, kids’ playrooms, gaming clubs, or any business where time is billed per person or per hour.


Built with Python and CustomTkinter, it features a clean dark interface, real-time tracking, and automated data management — all in one lightweight package.

- 🔧 Key Features
- ✅ Multiple user tracking — Add users by name; each user gets an individual timer that starts automatically.
- ⏱️ Synchronized operation — All timers run in parallel and remain perfectly synchronized, calculating costs in real time.
- 💰 Total overview — Automatically sums up total time and total cost across all users for an instant view of daily earnings.
- 📅 Date selection — Choose the working date before starting to maintain organized daily records.
- 💾 Auto-saving — All data is automatically saved into structured tables and stored as daily .csv files.
- 🔄 Load previous data — Reopening a saved date instantly restores and displays that day’s timers and results.
- 🛑 Individual control — Pause or stop each user’s timer independently from others.
- 📊 Reports and analytics — Generate detailed end-of-day summaries showing user names, time spent, and total cost.
- 🧾 PDF Reports — Export daily reports as polished PDF files for printing, archiving, or sharing with managers/clients.
- ⚙️ Flexible hourly rate — Fully customizable hourly rate, adjustable to your specific pricing model.

----------
🖥️ Interface
OrizonTimer offers a dark, modern, and minimal UI, built with CustomTkinter, optimized for clarity and ease of use.
Timers, controls, and totals are displayed in a structured layout with real-time updates.

-------------

⚙️ Requirements
Before running the app, install the required packages:
 - pip install customtkinter
 - pip install pandas
 - pip install pillow
 - pip install fpdf
(Optional for standalone build)
 - pip install pyinstaller

---------------------
 
🚀 Run the Application
Clone or download the project
Ensure all dependencies are installed
Run the app using:
 - python app.py

   -----------
Add users, start tracking, and generate reports instantly.
📦 Exporting to Executable (Optional)
To create a standalone .exe file:
 - pyinstaller --noconfirm --onefile --windowed main.py
💡 Summary
OrizonTimer simplifies time-based billing with automation, flexibility, and elegant design — perfect for any environment where time = money.

--------
by Kovacevic Arnel
