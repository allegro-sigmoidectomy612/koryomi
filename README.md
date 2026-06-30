# 📚 koryomi - Organize and read your digital manga

[![](https://img.shields.io/badge/Download-Koryomi-blue.svg)](https://github.com/allegro-sigmoidectomy612/koryomi)

Koryomi manages your entire manga and manhwa library. It tracks new releases, downloads files, and displays your collection in one interface. You avoid the need to run multiple separate programs to read your titles. Koryomi replaces individual tools for searching, downloading, and viewing content. It works as a self-hosted server that stays on your computer.

## 🛠 Features

*   **All-in-one management**: Search, track, and read in one program.
*   **Offline access**: Keep your files on your drive for reading without an internet connection.
*   **PWA support**: Install the reader directly to your desktop for a native experience.
*   **Media organization**: Sort your comics by series, chapter, or date.
*   **Universal reader**: Open standard file types like CBZ efficiently.

## 💻 System Requirements

*   **Operating System**: Windows 10 or Windows 11.
*   **Memory**: At least 4GB of RAM.
*   **Storage**: 500MB of space for the application plus extra space for your library.
*   **Network**: A stable internet connection to download new chapters.

## 🚀 Getting Started

You do not need programming knowledge to run this software. Follow these instructions to set up the application on your computer.

1.  **Visit the download page**: Go to [the official Koryomi releases page](https://github.com/allegro-sigmoidectomy612/koryomi) to find the correct version for your Windows computer.
2.  **Download the file**: Locate the file that ends in .exe. Click the name to start the download.
3.  **Run the installer**: Once the download completes, open the file. Your computer might show a security prompt. If you trust the source, click "Run" or "More info" followed by "Run anyway."
4.  **Complete the setup**: Follow the on-screen instructions to place the program in your preferred folder.

## ⚙️ Configuration

Start the program using the shortcut on your desktop or in your start menu. The application opens a local window. This window communicates with the background service that stores your library.

**Initial Setup**

When you open the application for the first time, choose a destination folder for your manga files. Pick a folder with enough space to grow as your library expands. The program creates subfolders for each series automatically to keep your drive organized.

**Adding Sources**

You must tell the software where to look for content. Navigate to the "Settings" tab and select "Sources." Here you can select the websites or databases that the program monitors. Toggle the switches next to your preferred sites to enable them. Koryomi will index the contents of these sites based on your settings.

## 📖 Using the Reader

The interface provides a library view where you see your currently tracked manga. Each cover image represents a series. Click a cover to view the chapter list.

*   **Reading a chapter**: Click any chapter title to launch the reader. Use your arrow keys or mouse to swipe through pages.
*   **Managing progress**: The application remembers the last page you viewed for every series. It resumes your progress when you return to a chapter.
*   **Filtering**: Use the search bar to filter your library by author, genre, or status (reading, completed, or dropped).

## ☁️ Running as a Service

The application runs as a background process. This allows the program to check for new chapters even when the main reader window is closed. You see a small icon in your system tray—the area near your clock on the taskbar. Right-click this icon to quit the application or open the dashboard.

If your computer turns off, the application stops. After you restart your computer, the application starts automatically to keep your library up to date. You can change this behavior in the "General" settings tab.

## 📁 File Management

Koryomi stores files in the CBZ format. This format packages your images into a single, portable file. If you move your library to a new computer, copy the folder containing your manga files and import the path in your new installation. The program scans the folder and detects the series automatically.

## 💡 Troubleshooting

**The application does not open**
Ensure you have the latest updates for Windows. If the issue persists, reinstall the application after removing the previous folder.

**The library shows no chapters**
Verify your internet connection. Check the "Logs" section in the settings menu. If an error appears here, the application cannot reach the chosen source sites. Ensure your firewall allows the application to access the network.

**The program feels slow**
Large libraries require more memory to index. If you have thousands of chapters, give the application a few minutes to process the initial scan. Avoid opening too many separate browser tabs while the initial scan runs.

## 🔒 Security and Privacy

Your data stays on your machine. Koryomi does not send your library metadata to external servers. Because you host the software, you control exactly who can access your content. If you share this machine with others, they might see your library and reading history. Keep your Windows user account secure to protect your personal information.

## 🔄 Updates

The application checks for updates automatically once per week. When an update is ready, a notification appears in the dashboard. Click the link in the notification to download the installer. Running the new installer replaces the older version while keeping your library and settings intact. You do not need to uninstall the old version manually. Every update improves the speed of the reader and adds support for new manga sources.