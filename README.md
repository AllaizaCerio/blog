# Pre-requisite
To successfully run the program, [ngrok](https://ngrok.com/download) must be installed. 
Create an account and configure the AuthToken in your device.

# How to run blog app
1. Download the project and install the dependencies by running the command below.
   ```
   npm install
   ```
3. Open three separate terminal.
4. On the first terminal, navigate to the jsonserver folder in the project and run the command below.
   ```
   npm run tunnel
   ```
6. Copy the link in the **Forwarding** section.
7. Open jsonServer.js file, found in blog/src/api directory.
   Replace the link in the baseURL with the link that was just copied.
   Save and exit the file.
8. On the second terminal, run the command below.
   ```
   npm run dev
   ```
10. On the third terminal, run the command:
   ```
   npm start
   ```
12. Scan the QR code to run project in mobile device. 
