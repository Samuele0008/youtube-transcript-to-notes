# 🎬 YouTube Transcript to Notes

Transform any YouTube video into structured, actionable notes in under 60 seconds—without paid apps, browser extensions, or manual transcription. All you need is your browser and an AI model.

📺 **Watch the full video tutorial on LinkedIn:** [Watch Video](https://lnkd.in/p/gcZYN7R9)

---

## 🎯 What You Can Do

- **Extract full YouTube transcripts** directly from your browser in seconds.
- **Convert raw transcriptions** into clean, well-structured summaries using AI.
- **Streamline learning** for lectures, tech tutorials, podcasts, market analyses, and interviews.

---

## 🛠️️ How It Works (Step-by-Step)

### Step 1: Open Developer Tools
Navigate to the YouTube video, right-click anywhere on the page, select **Inspect**, and switch to the **Network** tab.

### Step 2: Filter Requests
In the search/filter bar at the top of the Network panel, type:  
`timedtext`  
*(This isolates all network requests responsible for loading subtitles/captions.)*

### Step 3: Capture the Transcript Data
Play the video (or toggle subtitles on). A new request will appear in the Network list:
1. Double-click or click on the `timedtext` request.
2. Go to the **Response** tab.
3. Select and save the raw transcript file.

### Step 4: Process with AI
Paste the copied text into your preferred AI tool (Claude, ChatGPT, Gemini, etc.) alongside the system prompt provided in [`prompt.md`](./prompt.md).

---

## 📂 Repository Contents

| File | Description |
|---|---|
| [`prompt.md`](./prompt.md) | The exact prompt template to format raw transcripts into structured notes. |
| [`README.md`](./README.md) | Setup instructions and workflow guide. |

---

## 💡 Practical Use Cases

- 🎓 **Academic Lectures & Study Prep**
- 💻 **Coding & Technical Tutorials**
- ⚽ **Tactical Sports Analyses**
- 🎙️ **Podcasts & In-depth Interviews**
- 📈 **Financial & Market Research**
- 🧠 **Educational Content & Essays**

---

## 🤝 Contributing

Got a more optimized prompt? Developed a quick script to automate the extraction step?  
Contributions are welcome! Feel free to open an **Issue** or submit a **Pull Request**.

---

## 📄 License

Distributed under the MIT License. See [`LICENSE`](./LICENSE) for more details.
