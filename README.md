# Advanced YouTube Downloader & Smart Assistant

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://www.javascript.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

This project is a single-page YouTube video/audio download simulation tool with a modern and user-friendly interface. In addition to standard download features, it offers intelligent analysis and summaries of video content through its Google Gemini API integration.

---

*You can make the project more appealing by adding a screenshot here. Update the line below with the path to your own screenshot.*

---

### ✨ Key Features

- **Multi-Format Support:**
  - **Video Downloading:** Simulation of video downloads in various qualities (1080p, 720p, 480p, 360p).
  - **Audio (MP3) Downloading:** Simulation of downloading videos in high-quality MP3 format.

- **🤖 Gemini Smart Assistant:**
  - **Detailed Summary:** Generate a comprehensive summary of the video's main ideas and key points.
  - **Title Suggestions:** Propose 5 alternative, SEO-friendly, and catchy titles for the video.
  - **Keywords:** Extract relevant keywords and long-tail keywords based on the video's content.
  - **Target Audience Analysis:** Analyze the potential audience of the video, including demographics and interests.
  - **3-Point Summary:** Quickly summarize the most critical points of the video in just three bullets.

- **User Experience:**
  - **Light & Dark Theme:** Modern interface themes that adapt to system preferences or user selection.
  - **URL History:** Stores recently entered video URLs in the browser for quick access.
  - **Advanced Settings Panel:** Manage preferences like default download quality, theme selection, and history.
  - **Responsive Design:** A seamless user experience on both desktop and mobile devices.
  - **Instant Feedback:** Dynamic message boxes to show the status of operations (success, error, loading).

---

### 🚀 Technologies Used

- **Frontend:**
  - **HTML5:** The structural backbone of the page.
  - **Tailwind CSS:** A utility-first CSS framework for rapid and modern design (via CDN).
  - **Vanilla JavaScript:** Powers all dynamic functionality, API integration, and DOM manipulation.
- **API:**
  - **Google Gemini API:** Used for all video content analysis and summarization features.

---

### 🛠️ How to Use

This project is a single HTML file that requires no server or build process.

1.  **Clone or Download the Project:**
    ```bash
    git clone [https://github.com/vkaiber/ytvideodownloader.git]
    ```

2.  **Get a Gemini API Key:**
    - Go to [Google AI Studio](https://aistudio.google.com/app/apikey) and create a free API key.

3.  **Add the API Key:**
    - Open the `yt.html.html` file in a text editor.
    - Find the following line in the JavaScript section:
      ```javascript
      const GEMINI_API_KEY = ""; // Will be provided automatically in a Canvas environment.
      ```
    - Paste your Gemini API key between the double quotes.

4.  **Open in a Browser:**
    - Open the `yt.html.html` file directly in your favorite web browser. That's it!

---

### ⚠️ Important Disclaimer

This application was developed as a proof-of-concept and a user interface demonstration. The terms of service for YouTube prohibit unauthorized downloading of videos. It is the user's sole responsibility to **respect copyright and platform policies** when using such tools. This interface does not encourage any illegal activity.

---

### 🤝 Contributing

Contributions are always welcome! Please read the contribution guidelines before opening an issue or pull request.

1.  **Fork** the Project.
2.  Create your **Feature Branch** (`git checkout -b feature/AmazingFeature`).
3.  **Commit** your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  **Push** to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a **Pull Request**.

---

### 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

### ☕ Support

If you like this project and want to support its development, you can buy me a coffee!

<a href="https://www.buymeacoffee.com/victorkaiber" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" >
</a>
