# INTERNSHALA--AUTOAPPLY-BOT 💻
An automation tool using Puppeteer, Node.js, and JavaScript to streamline Internshala applications. It logs in, fills resume details, and applies for internships with custom responses, saving time and effort. Features include auto-login, resume auto-fill, smart submissions, and efficient bulk applications. 🎯

✨ Overview

Internshala AutoApply Bot is an automated script designed to streamline the internship application process on Internshala. Built with Puppeteer, Node.js, and JavaScript, this bot automates resume completion and internship applications, reducing manual effort and increasing efficiency.

💡 Features

✅ Automated Login - Securely logs into Internshala with user credentials.✅ Smart Resume Builder - Auto-fills graduation, training, and work samples from pre-defined data.✅ Bulk Internship Applications - Automatically applies for internships from a specified fair page.✅ Custom Responses - Submits applications with personalized answers.✅ Time Optimization - Reduces manual effort and saves time.

📂 Installation & Setup

1. 📚 Clone the Repository

 git clone https: https://github.com/GitHubKanahiya/INTERNSHALA--AUTOAPPLY-BOT.git
 cd Internshala-AutoApply-Bot

2. 🔧 Install Dependencies

Ensure Node.js and npm are installed, then install Puppeteer:

npm install puppeteer

3. 🔐 Configure Credentials & Data

Update secret.js with your Internshala login details:

const credentials = {
  id: "your-email@example.com",
  pass: "your-password"
};
module.exports = credentials;

Modify data.js with your resume details (e.g., college, degree, training, work samples).

4. 🚀 Run the Script

Execute the main script using:

node script.js

🔎 Notes

Adjust timeouts (setTimeout) based on network speed & system performance.

Ensure selectors (waitForSelector) match the latest Internshala UI.

Keep your credentials secure and never expose them in public repositories.

💌 Contribution

We welcome contributions! If you have ideas for improvement, open an issue or submit a pull request.For major changes, create an issue first to discuss the proposal.

📡 Disclaimer

This bot is intended for educational purposes only. Use responsibly, and ensure compliance with Internshala's terms and conditions.

🌟 Show Some Love

If you found this project useful, give it a star (⭐) on GitHub and share it with fellow developers!

👉 GitHub Repository  https://github.com/GitHubKanahiya/INTERNSHALA--AUTOAPPLY-BOT.git


