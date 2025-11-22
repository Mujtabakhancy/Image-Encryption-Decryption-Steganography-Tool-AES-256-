# Image-Encryption-Decryption-Steganography-Tool-AES-256-
This project is a complete Image Encryption, Decryption, and Steganography system developed to demonstrate secure image handling. The tool combines two important security techniques: AES-256 encryption and LSB-based image steganography. Its purpose is to provide a simple way to protect images and also hide secret text messages inside images without changing their appearance.

The project includes a basic login system to prevent unauthorized access. The default credentials are:
Username: admin
Password: pass

After logging in, the user can choose to encrypt an image, decrypt an encrypted image, hide a secret message inside an image, or extract a hidden message from an image.

The encryption feature uses the AES-256 algorithm, which is one of the most secure and widely used encryption standards. When an image is encrypted, it becomes unreadable to anyone who does not have the correct key. This ensures that the image stays protected during storage or transfer.

The decryption feature reverses the encryption process and restores the original image. Only the correct AES key can decrypt the image, which adds an additional layer of security.

The steganography feature uses the Least Significant Bit (LSB) technique to hide text inside an image. The hidden message cannot be seen by looking at the image, and it can only be retrieved using the extraction function built into the tool. This method is commonly used for private communication and data protection.

The project is built using Python, Tkinter for the graphical interface, the cryptography library for AES-256 implementation, and PIL/OpenCV for image handling. It is designed to be beginner-friendly and is useful for students, researchers, and anyone interested in learning about encryption, steganography, and cybersecurity.

This repository provides an easy way to understand how encryption and hidden data techniques work together. It can also be extended or improved based on user requirements.
