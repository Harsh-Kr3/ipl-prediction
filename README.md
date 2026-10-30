# 🏏 IPL 2026 Engine Simulator Pro

An interactive, feature-rich frontend web application built to simulate the complete **IPL 2026** season (all 74 matches), featuring real-time **Points Table calculations**, dynamic **Net Run Rate (NRR) adjustments**, **team form tracking**, and a fully automated **[TBD] Playoff Knockout Bracket** (Qualifier 1, Eliminator, Qualifier 2, and Grand Final).

---

## ✨ Key Features

*   **Complete 74-Match Schedule:** Covers all 70 regular season league matches followed by the championship playoffs.
*   **Live Points Table & NRR Engine:** 
    *   Automatically updates Matches Played (P), Wins (W), Losses (L), and Points (+2 per win).
    *   Dynamic NRR calculation based on your selected match victory margins (**Runs** or **Wickets Left**).
    *   Automated tie-breaker sorting using points and NRR rankings.
*   **Smart Playoff Bracket (`[TBD]` Matrix):** 
    *   Positioned directly below the league fixtures stream.
    *   Stays locked with `[TBD]` placeholders until all 70 regular league matches are predicted.
    *   Automatically locks in the **Top 4 teams** from the standings table into Qualifier 1 and the Eliminator once unlocked.
*   **Per-Match Controls & Indicators:**
    *   **Prediction Badges:** Instantly shows a green `● Predicted` indicator on matches you've locked in.
    *   **Single-Match Reset:** Easily clear an individual match's prediction without resetting the entire tournament.
*   **Recent Form Guide:** Displays a visual 5-match form history tracker (`W W L W L`) next to each team in real-time.
*   **Quick Simulation:** Features a *"Simulate Remaining Randomly"* button to auto-fill unpredicted matches with realistic randomized victory margins.
*   **Persistent Storage:** Uses your browser's `LocalStorage`, meaning your progress and custom predictions won't disappear if you refresh or close the tab.
*   **Modern UX/UI Design:** Built with a clean layout, responsive grid design, and official franchise color-accent borders for every team.

---

## 🚀 How to Run the Project Locally

Since this is a pure frontend application built using **HTML, CSS, and Vanilla JavaScript**, you don't need to install any complex backend servers, databases, or Node.js packages!

### Method 1: The Quick Way (Direct Browser Open)
1. Clone or download this repository to your computer.
2. Locate the project folder and find your `index.html` file.
3. **Double-click** `index.html` (or right-click and choose **Open with > Google Chrome** / your preferred browser).

### Method 2: The Developer Way (Using VS Code & Live Server)
1. Open **VS Code**.
2. Go to **File > Open Folder** and select your project directory.
3. Install the **Live Server** extension by Ritwick Dey from the VS Code Marketplace (if you haven't already).
4. Open `index.html`, right-click anywhere in the code editor, and select **"Open with Live Server"** (or click the *Go Live* button at the bottom-right corner of VS Code).
5. The application will open automatically in your browser with live-reloading enabled.

---

## 🛠️ How to Use the Simulator

1. **Predict Match Outcomes:** Scroll through the *Regular Season Fixtures Stream*, click on the team you think will win a match, and adjust their winning margin (Runs or Wickets) using the input box.
2. **Track the Standings:** Watch the *Live Point Table Standings* on the left instantly update ranks, points, form guides, and NRR values.
3. **Reset Options:** 
   * Click **"Reset Game"** on any individual match card to clear just that specific prediction.
   * Click **🔄 Reset All Data** at the top right to wipe everything and start fresh.
4. **Unlock the Playoffs:** Once all 70 league fixtures are completed and predicted, the bottom **Championship Knockout Playoffs Matrix** will unlock, allowing you to simulate Qualifier 1, Eliminator, Qualifier 2, and crown your **Tournament Champion**!

---

## 💡 Tech Stack
* **HTML5 Markup** (Semantic structure & layout containers)
* **CSS3 Styling** (Custom variables, flex/grid layouts, dynamic border-accents, and scrollbar utilities)
* **Vanilla JavaScript (ES6+)** (State management, event handlers, NRR arithmetic calculations, and conditional DOM rendering)
* **Browser LocalStorage API** (Data persistence)

---

## 📄 License
This project is open-source and free to use for personal entertainment and tournament forecasting.
