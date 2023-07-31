File Organizer Script
The File Organizer Script is a bash script designed to organize files into specific directories based on their file extensions. It helps keep your files more organized and tidy by sorting them into categories such as images, documents, videos, scripts, and audios.

Prerequisites
Make sure you have the following installed on your system:

Bash (usually pre-installed on Linux and macOS)
find command (usually available on most Unix-like systems)
Usage
Download the script to your system.
Make the script executable: chmod +x file_organizer.sh
Run the script: ./file_organizer.sh
Supported File Extensions
The script organizes files with the following extensions:

Images
- jpg - png - gif
jpeg
bmp
tiff
webp
svg
ico
psd
Documents

pdf
json
csv
txt
doc
docx
xls
xlsx
ppt
pptx
odt
ods
odp
rtf
xml
Scripts

sh
py
c
cpp
java
js
php
pl
rb
swift
bash
ps1
bat
cmd
Audios

mp3
wav
ogg
flac
m4a
aac
wma
aiff
ape
alac
opus
mid
amr
ra
Videos

mp4
avi
mkv
gif
wmv
m4v
m4p
mpg
mpeg
flv
nsv
mxf
viv
Script Execution
The script will organize files in the specified $main_directory/file_structure directory. It will create sub-directories for each category (images, documents, videos, scripts, and audios) and move the respective files into these sub-directories based on their file extensions.

Please note that the script will not delete any files but only organize them. Any sub-directories that become empty after the organization will be removed.

Important Note
Please use this script responsibly and always keep a backup of your important files before running any file organization scripts.

License
This script is open-source and released under the MIT License. See the LICENSE file for details.

For more information on how to use the script and its functionalities, refer to the inline comments and function descriptions within the script. If you have any questions or feedback, feel free to reach out.

License Recommendation
The MIT License is commonly used for open-source software and is permissive, allowing users to use, modify, and distribute the code with limited restrictions. It is widely accepted and user-friendly for both developers and end-users. Therefore, the MIT License is recommended for this File Organizer Script.
