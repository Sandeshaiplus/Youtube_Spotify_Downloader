
# YouTube & Spotify Downloader 🎵💻

This Python script empowers you to effortlessly download your favorite tracks from both YouTube and Spotify, enabling offline enjoyment of your music collection.

## Features 🚀

- **YouTube Download:** Download audio tracks from YouTube by providing either the song name or its YouTube link.
- **Spotify Download:** Access songs from Spotify via their corresponding links.
- **File Management:** The script intelligently manages downloads, preventing duplicates and ensuring a clutter-free workspace.
- **Logging:** Comprehensive logging provides transparency and facilitates easy troubleshooting.
- **Checksum Verification:** Ensure the integrity of downloaded files using SHA-256 checksum verification.

## Prerequisites 🛠️

- **Python 3:** Ensure Python 3 is installed on your system.
- **Path:** Ensure to give the correct path of the executable you downloaded to the query when program asks
- **enter:** Enter the full path of the exe location
- For Windows: 
  ```bash
      path to downloadai.exe
   ```
-For Linux:
  ```bash
      path to downloadai or ./downloadai if in current dir!
   ```
-**FFMPEG:** Make sure to have ffmpeg installed as plays a crucial role in merging the downloaded data.



-**For Windows:** Download ffmpeg from [here](https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z) or use the given one by me simply extract the ffmpeg.zip and add the bin folder to environment variable
-**For linux:**
 ```bash
      sudo apt install ffmpeg
   ```
- **if error:**
```bash
     sudo apt update &&  apt upgrade
     sudo apt install ffmpeg --fix-missing
   ```

## Usage 📋

1. **Clone Repository:**
   ```bash
   git clone https://github.com/Sandeshaiplus/Youtube_Spotify_Downloader.git
   cd Youtube_Spotify_Downloader
   ```

Certainly! Here's the revised section with emojis and platform-specific instructions:

---

## Run Script 🚀

1. **Navigate to the Repository:**

   Change your current directory to the location of the YouTube & Spotify Downloader script.
   
   ```bash
   cd Youtube_Spotify_Downloader
   ```
Thank you for your patience! Here's the revised section:

---

## Add Executable to Environment Variable 🛠️

### For Windows:

1. **Locate the Executable:**
   
   Find the `downloadai.exe` file in your project directory.

2. **Add to Path:**

   - Right-click on the **Start** button and select **System**.
   - Click on **Advanced system settings**.
   - In the System Properties window, click on **Environment Variables**.
   - Under System Variables, select **Path**, then click **Edit**.
   - Click **New** and add the directory path where your `downloadai.exe` file is located.
   - Click **OK** to save the changes.

3. **Verify Installation:**

   Open a new command prompt and type `downloadai.exe`. If the installation was successful, the command should execute without errors.

### For Linux:

4. **Locate the Executable:**

   Find the executable file named `downloadai` in your project directory.

5. **Move to Bin Directory:**

   - Open a terminal and navigate to the directory containing your executable.
   - Copy the executable to the `/usr/local/bin` directory using the following command:
   
     ```bash
     sudo cp downloadai /usr/local/bin/
     ```

6. **Provide Execution Permissions:**

   Ensure that the executable has the necessary permissions to run. If not, grant execution permissions using the following command:

   ```bash
   sudo chmod +x /usr/local/bin/downloadai
   ```

7. **Verify Installation:**

   Open a new terminal and type `downloadai`. If the installation was successful, the command should execute without errors.

---

This section provides instructions for adding the `.exe` file to the system's environment variable for both Windows and Linux operating systems. The executable name is set to `downloadai.exe` for Windows and `downloadai` for Linux.


8. **Execute the Script:**

   Run the script to initiate the download process. Use the following command:

   - For Windows:
   
   ```bash
   downloadai.exe
   ```

   - For Linux:
   
   ```bash
   ./downloadai
   ```

9. ***Follow On-screen Instructions:***

Upon running the script, you'll be prompted with options for downloading content.

For Spotify downloads:
Enter the Spotify song link when prompted.
The script will notify you of any errors and provide guidance on correcting them.
For YouTube downloads:
Choose between downloading by song name or YouTube link.
If downloading by name:
Enter the song name.
Provide the download location when prompted, or leave it blank for the current directory by simply pressing Enter.
The script will default to the current working directory (CWD) if no location is specified.
If downloading by YouTube link:
Enter the YouTube video link.
Similarly, provide the download location if prompted.
The script will validate inputs and provide feedback for any corrections needed.
Follow the on-screen prompts to proceed with the download.

---

This section offers a detailed guide for executing the script, ensuring a smooth experience for users, with clear instructions and prompts, including platform-specific commands.

**command's**

  for exit
  ```bash
          00
   ```

  for options 'as shown on program'.
---------------------
## Logging and Troubleshooting 📝

- All activities are meticulously logged in `download_log.log`, facilitating easy troubleshooting and error identification.

## Contributors 🤝

- [Sandesh Kumar](https://github.com/Sandeshaiplus)

## Support ℹ️

For any inquiries, issues, or suggestions, please reach out to support@sandeshai.in.

---

This README.md aims to provide comprehensive guidance on utilizing the YouTube & Spotify Downloader script effectively. Let the music downloading adventure begin! 🎶🔥
