IMAGE ENCRYPTION AND DECRYTPION

This project is a web-based tool that securely encrypts and decrypts images using AES-256 encryption and Argon2ID hashing. 
It features a Flask backend and a user-friendly web interface (LOCAL HOST) for quick encryption and decryption.

-- How It Works
   > Encryption:
      // Upload an image.
      // Enter a secure password.
      // The app encrypts the image and downloads it as a .txt file.
   > Decryption:
      // Upload the encrypted .txt file.
      // Enter the same password.
      // The app restores the original image.

-- Technologies Used
   > Python (Flask) — Backend server
   > HTML, CSS, JavaScript — Web interface
   > cryptography library — AES-256 encryption
   > argon2-cffi — Argon2ID password hashing

-- How To Run
   1. pip install <package>
      ... flask
      ... cryptography
      ... argon2-cffi
      replace the <package> with the package names given
   2. git clone https://github.com/whoknows-md/EDImage.git
   3. cd EDImage
   4. python app.py

Happy Encrypting !!  
