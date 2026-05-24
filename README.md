# CricMind AI — Elite AI Cricket Coach & Match Strategy Planner

**CricMind AI** is an extremely premium, dark stadium-themed, production-grade AI-powered cricket coaching client and tactical analyzer built for players, fast bowlers, captains, and wicketkeepers to bridge the coaching gap. 

Designed and engineered for the **APL Gwalior Hackathon**, CricMind AI incorporates high-performance browser-based **React**, **Tailwind CSS**, the **Web Speech API** (for bidirectional voice speech commands and dramatic commentary audio playouts), **Google Gemini 1.5 Flash API**, and **Firebase Firestore** for real-time cloud database syncing.

---

## 🌟 Key Features

### 1. 🤖 AI Coach Room
- Speeds up player development with customized coaching triggers (Batter, Bowler, Captain, Keeper).
- Delivers highly structured, actionable coaching plans: **Weakness Analysis**, **Drill Plan** (3 clear, numbered steps), **Key Tips**, **Pro Player Reference**, and **Coach's Word** (energetic, motivational quotes).
- **Voice Speech Recognition:** Speak your queries directly to the coach using native microphone input.
- **Voice Speech Synthesis:** The coach *speaks* its technical feedback back to you in an Indian English accent for natural stadium realism.

### 2. 🏟️ Dynamic Unified Action Bridge
An advanced, computer vision-inspired bypass engine linking coach sessions directly to visual boards:
- **stadium (Live Arena Shortcut)**: Clicking **"🏟️ Play in Stadium"** under bowling/spin queries automatically pre-fills the pitch condition (*Dry Spinning*) and opponent type (*Spin Heavy*) and bypasses you directly to the tactics board.
- **posture (Posture Lab Shortcut)**: Clicking **"🔍 Upload Stance"** under stance trigger queries immediately jumps you to the vision scanner.
- **strategy (Tactics Board Shortcut)**: Clicking **"🗺️ Tactics Board"** immediately redirects you to the Strategy Page.

### 3. 📊 Match Strategy & Interactive SVG Field Planner
- Input match parameters (Opponent style, Pitch type, Overs left, Wickets lost).
- Dynamic **Aggression Meter** and **Win Probability Charts** recalculate in real-time.
- **Interactive SVG Field Map:** Automatically renders defensive or aggressive positions. **Tap on any fielder dot to view their exact tactical role in real-time!**

### 4. 🎙️ Live Commentary Mic (Radio Room)
- Generates Ravi Shastri / Harsha Bhogle style electrifying live cricket commentary with dynamic Hindi catchphrases.
- Quick event triggers: **SIX!**, **FOUR!**, **WICKET OUT!**, **DOT BALL**, **NO BALL**, **REVIEW LBW**, and **CENTURY!**
- Live synthesized vocal playout reads commentary with high-energy crowd atmosphere context.

### 5. 📸 Batting Posture Vision Lab
- Screenshot stance analyzer mockup for scorecard parsing or bat swing checks.
- Pre-baked **Stance Posture** and **Scorecard presets** to demonstrate vision capabilities instantly without uploading files.

### 6. 📈 Stats & Progress Dashboard
- An interactive **5-Axis SVG Radar Chart** mapping Batting, Bowling, Fielding, Strategy, and Mental traits.
- Dynamic strengths progress meters.
- Streaks counter and AI Performance Index tracking.

---

## 🛠️ Technology Stack
- **Frontend Core**: React 18, Tailwind CSS (glowing glassmorphic layout, stadium-themed gradients).
- **AI Core**: Google Gemini 1.5 Flash API, CricMind Vision model.
- **Backend Database**: Firebase Firestore (real-time live cloud sync of coaching logs and commentaries).
- **Voice Core**: Web Speech API (Speech-to-Text SpeechRecognition & Text-to-Speech SpeechSynthesis).
- **Visuals**: Native inline SVGs (Radar Chart & Interactive Field Placement Map).

---

## 🚀 How to Run & Verify

1. **Clone/Download the repository**: Make sure all files (`index.html`, `cricmind-v2.html`, etc.) are in your folder.
2. **Double-click** `index.html` to run it instantly in any modern web browser (Google Chrome or Microsoft Edge are highly recommended for full Speech recognition support).
3. **No Setup Needed:** If no Gemini API key is entered, the app seamlessly runs on a high-fidelity **AI Simulator** to demonstrate the "Killer Demo Flow" flawlessly!

---

## 🎯 The "Killer Demo Flow" for Judges

1. Open `index.html`. Watch the custom **Cricket Ball Loader** spin.
2. Go to the **AI Coach Room**, select **Batter** role.
3. Speak or type: 
   > *"I struggle against spin bowling"*
4. Inspect the highly structured technical drills, pro references, and listen to the coach's audio instructions.
5. Click **"🏟️ Play in Stadium"** in the Unified Action Bridge below the reply.
6. Verify that the **Tactics Room** loads with *Dry Spinning* and *Spin Heavy* pre-filled.
7. Click **Generate Team Strategy Card**. Inspect the dynamic **Aggression Meter**, **Win Probability**, and tap on the **Slip** or **Point** dots on the interactive field map.
8. Go to the **Live Mic** tab and click **SIXER!** to generate and vocalize Ravi Shastri style live commentary.
