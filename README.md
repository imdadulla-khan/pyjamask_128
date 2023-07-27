# Pyjamask128 Encryption and Decryption - Client-Server Application

This repository contains an implementation of Pyjamask-128 encryption and decryption using a Client-Server Application. Pyjamask-128 is a block cipher algorithm designed for lightweight applications, and its working details can be found in the provided PDF.

To run the application, follow the steps below:

Step 1: Clone the repository and navigate to it in your terminal.

Step 2: Open two separate terminals.

Step 3: In the first terminal, run the server script using the command:


python3 server.py
The server will start listening on the specified port mentioned in the code.

Step 4: In the second terminal, run the client script using the command:


python3 client.py
## Encryption Process:

After running the client script, you will be prompted to choose the encryption process. Enter 1 and press Enter.

Next, enter the plain text that you want to encrypt.

Then, enter the 16-hex-value key (hex values like 123456789abcdef) that you wish to use for encryption.

The client will send this information to the server, which will encrypt the plain text using Pyjamask-128 with the provided key.

The server will respond by sending the encrypted text back to the client.

## Decryption Process:

After running the client script, you will be prompted to choose the decryption process. Enter 2 and press Enter.

Next, enter the cipher text in binary form (128 bits) that you want to decrypt.

Then, enter the 16-hex-value key that you used for encryption.

The client will send this information to the server, which will decrypt the cipher text using Pyjamask-128 with the provided key.

The server will respond by sending the decrypted text back to the client.

Please make sure to provide the correct inputs for the encryption and decryption processes to ensure accurate results.

Feel free to experiment with the Pyjamask-128 encryption and decryption using this client-server application. If you encounter any issues or have any questions, refer to the PDF for more details or consult the code in server.py for the Pyjamask-128 implementation.
