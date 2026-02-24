📂 Portable Suite Structure (Important)
ParrMotion is a portable, no-installation utility. To ensure high-definition video processing and playback verification, the following components should be kept in the same folder:

ParrMotion.exe — The primary user interface and logic controller.

ffmpeg.exe — (Essential) The core engine used for merging high-quality video and audio streams.

ffprobe.exe — (Essential) The analysis tool used to detect media metadata and resolutions.

ffplay.exe — (Optional) A lightweight media player used by the engine for technical stream verification.

Note: While ffplay.exe is not strictly required for the core download/merge process, keeping all four files together ensures maximum compatibility with all yt-dlp backend features.

🚀 ParrMotion Downloader v1.0.0
ParrMotion is a minimalist, high-performance web media acquisition utility. Built for speed and reliability, it provides a seamless interface for downloading high-fidelity video and audio from thousands of platforms globally.

💎 Engineering Excellence
Core Engine: Powered by the industry-standard yt-dlp framework, ensuring deep compatibility and constant updates for global media sites.

AI-Driven Architecture: This software was architected and refined through intensive engineering collaboration with Google Gemini 3.1 Pro. The codebase emphasizes stability, cross-platform UI consistency, and efficient resource management.

✨ Key Capabilities
🌍 Multi-Regional Localization: Intelligent auto-detection and manual switching for English, Simplified Chinese, Traditional Chinese, Japanese, and Korean.

🎨 Adaptive UI Interface: Fully integrated Dark Mode support for an immersive, eye-friendly user experience in any environment.

⚡ Precision Rate Limiting: Advanced bandwidth management allowing users to set explicit speed caps (MB/s) or leave blank for unrestricted throughput.

🛡️ Robustness Features:

Collision Prevention: Implements a unique 4-character task-ID algorithm to prevent file overwrites during concurrent or repeated downloads.

Resolution Feedback: Real-time identification and display of the actual video resolution (e.g., 4K, 1080p) during the extraction phase.

Automated Cleanup: Built-in garbage collection logic that automatically purges temporary .part or .ytdl files if a process is interrupted.

🛠️ Execution & Deployment
ParrMotion is designed as a portable, "green" software suite requiring no installation.

Main Executable: ParrMotion.exe

Required Binaries: Both ffmpeg.exe and ffprobe.exe must be placed in the same directory as the main executable to enable high-definition media merging and analysis.

👨‍💻 Development Information
Powered by yt-dlp

Consulting AI: Google Gemini 3.1 Pro

Version: v1.0.0 (Stable)

Contact: srlee717421@gmail.com
