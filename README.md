# Hash Snitch

Hash Snitch is a modern, user-friendly web application that allows users to calculate and verify file hashes using popular algorithms such as SHA-256, SHA-1, and MD5. The app supports drag-and-drop file uploads and enables easy comparison with known hashes for file integrity verification.

## Features

* Calculate file hashes (SHA-256, SHA-1, MD5) directly in the browser
* Drag & drop files or browse to select files
* Compare calculated hashes with known hashes
* Responsive, clean, and intuitive user interface

## Work in Progress

This project is still under active development. An important upcoming feature will be integration with [VirusTotal](https://www.virustotal.com/) to scan files for malware and security threats directly from the application.

## Usage

1. Drag & drop your files into the drop zone or click to browse and select files.
2. Choose the desired hash algorithm from the dropdown menu.
3. Wait for the hash calculation to complete.
4. Optionally, paste a known hash to compare against your files.
5. Click **Compare** to verify if your file matches the known hash.

## Technologies Used

* HTML, CSS, JavaScript
* [SparkMD5](https://github.com/satazor/js-spark-md5) for MD5 hashing
* Web Crypto API for SHA-1 and SHA-256
* Google Fonts for typography

## License

MIT License
