Desktop Cleaner

This Python script monitors a specified directory for new files and categorizes them into different folders based on their file type. It's particularly useful for organizing files downloaded from the internet or received from various sources.
Features

    Monitors a source directory for new files and automatically categorizes them into destination directories based on their file types.
    Supports categorization of audio, video, image, and document files into separate directories.
    Provides options to differentiate between sound effects (SFX) and music files.

How to Use
    
    Ensure you have Python installed on your system.
    Install the required libraries by running:

bash

pip install watchdog

Open the script and configure the following variables in the "FILL IN BELOW" section:

    source_dir: The directory to monitor for new files.
    dest_dir_sfx: Destination directory for sound effect files.
    dest_dir_music: Destination directory for music files.
    dest_dir_video: Destination directory for video files.
    dest_dir_image: Destination directory for image files.
    dest_dir_documents: Destination directory for document files.

Optionally, you can modify the supported file extensions for each category by updating the respective lists (image_extensions, video_extensions, audio_extensions, document_extensions).
Run the script by executing the following command in your terminal or command prompt:

bash

    python main.py

    The script will continuously monitor the specified source directory for new files and categorize them accordingly.

Additional Notes

    The script utilizes the watchdog library for monitoring file system events, ensuring efficient and real-time processing of new files.
    You can customize the behavior of the script by modifying the MoverHandler class methods to suit your specific requirements.

Feel free to contribute to this project by adding new features or improving existing ones. If you encounter any issues or have suggestions for enhancements, please create an issue or submit a pull request on GitHub. Happy file organizing!

PS: Would love to have the option to cease the listener when certain keyboard shortcut is pressed e.g.
