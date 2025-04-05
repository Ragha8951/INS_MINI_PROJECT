# Digital Signature Scheme

## Summary
This project implements a **Digital Signature Scheme (DSS)** using Flask and Python's `cryptography` library. It allows users to register, generate keys, sign messages, verify signatures, and generate/view/verify certificates.

### Simple Explanation
A digital signature is like an electronic fingerprint. It ensures the authenticity and integrity of a message.

#### Example:
1. Alice registers and gets a private and public key.
2. She writes "Hello Bob" and signs it using her private key.
3. Bob receives the message and the signature.
4. Bob verifies the signature using Alice's public key.
5. If the signature is valid, he knows the message came from Alice and wasn't changed.

## Real-time Use Cases
- Secure email communication.
- Software integrity validation.
- Digital contracts and e-signatures.
- Certificate generation and validation.

## Libraries Used
- Flask – Web framework
- SQLAlchemy – Database ORM
- cryptography – For DSA key generation, signing, and verifying
- json – For handling certificate data

## How to Run the Code
1. Clone the repository or download the source code.
2. Install dependencies:
   ```bash
   pip install flask cryptography flask_sqlalchemy
   ```
3. Run the Flask app:
   ```bash
   python app.py
   ```
4. Open your browser and visit:
   [http://127.0.0.1:5000](http://127.0.0.1:5000)

## What to Expect
- A webpage with a clean user interface.
- Register users and generate DSA keys.
- Send and sign messages.
- Verify message authenticity.
- Generate and verify digital certificates.
- Visual feedback if the message is tampered.

## Future Enhancements
- Add download options for keys and certificates.
- Email notifications when a message is received.
- Role-based access controls.
- End-to-end encryption for message delivery.
- Full certificate authority (CA) integration.

## Contribution
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to create a pull request or open an issue.

## Author
- GitHub: [@Ragha8951](https://github.com/Ragha8951)
- Email: ragha8951@gmail.com

## Google Colab Link
[Run on Google Colab](https://colab.research.google.com/drive/1qvsRfLlnSTD4EO1_XSN6c8PH6Ojy5Foh?usp=sharing)

## Launch Webpage Using Flask
[http://127.0.0.1:5000](http://127.0.0.1:5000)

