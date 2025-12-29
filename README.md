# Scribe.AI 🎙️🎲

**Scribe.AI** is your intelligent companion for Dungeons & Dragons and Tabletop RPG sessions. It acts as an automated scribe, listening to your voice channel to transcribe the action and generating detailed, narrative summaries of your adventures using Google Gemini AI.

It also serves as an AI Dungeon Master assistant to answer rule questions and an image generator to visualize your campaign on the fly.

![Bot Icon](https://github.com/benjamin4pres-scribe/scribe.ai/raw/main/Scribe_AI_Logo.png)

## ✨ Key Features

* **🎙️ Automatic Journaling:** No more taking messy notes. Scribe.AI listens to the session and writes a recap for you.
* **🤖 AI DM Assistant:** Stuck on a rule or need a quick NPC name? Ask the bot with `/ask`.
* **🎨 Instant Visuals:** Describe a monster or item, and use `/image` to show the party what it looks like.
* **📌 Smart Bookmarking:** Use `/note` to feed specific details to the AI, or `/mark` to timestamp epic moments.
* **☁️ Slash Commands:** Easy-to-use interface directly within Discord.

## 🔗 Add to Your Server

**[Click here to invite Scribe.AI to your server](https://discord.com/oauth2/authorize?client_id=1444110469236265041&permissions=70379584&integration_type=0&scope=applications.commands+bot)**

This link grants the bot the following required permissions:
* **Voice:** Connect, Speak
* **Text:** Send/Manage Messages, Embed Links, Attach Files, Read History, Add Reactions
* **General:** Change Nickname (for status updates)

## 📖 How to Use

### 1. Start the Session
Join a voice channel with your party. When you are ready to begin, type:
`/join`
The bot will join the channel and change its nickname to **🔴 AI Recorder**.

### 2. Play Your Game
Play as normal! The bot will handle the note-taking.
* **Tip:** If you find a specific item or meet a key NPC, use `/note Found the Sword of Truth` to ensure the AI highlights it in the summary.
* **Tip:** Need a break? Use `/pause` and `/resume` to control the recording.

### 3. Wrap Up
When the session ends, type:
`/leave`
The bot will leave the voice channel, process the audio, and post a comprehensive summary of the session to the chat.

## 🎮 Command Reference

| Command | Description |
| :--- | :--- |
| **Session Control** | |
| `/join` | Summon the bot to your voice channel to start recording. |
| `/leave` | End the session, process audio, and generate the summary. |
| `/pause` | Temporarily pause recording (good for breaks). |
| `/resume` | Resume recording after a pause. |
| **AI Tools** | |
| `/ask [question]` | Ask the AI DM a question about rules or lore. |
| `/image [prompt]` | Generate a fantasy image based on your description. |
| `/scene` | Visualize the current scene based on your recent `/note` history. |
| **Utilities** | |
| `/note [text]` | Add a specific detail for the AI to remember. |
| `/mark` | Bookmark a timestamp (useful for editing later). |
| `/clean` | Delete temporary files (Admin use). |
| `/health` | Check bot status and uptime. |
| `/tidy` | Clean up bot commands from the chat window. |

## ⚖️ Legal & Privacy

* **Terms of Service:** [Read Here](terms_of_service.md)
* **Privacy Policy:** [Read Here](privacy_policy.md)

**Important:** This bot records audio for the purpose of summarization. By using the `/join` command, you acknowledge that you have obtained consent from all users in the voice channel to be recorded.

## 🤝 Support

Created by **thepawnking**. If you encounter issues or have feature requests, please reach out via Discord!
