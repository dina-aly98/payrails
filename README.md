#This is my case study for Question 1. This is the first time I've utilized any of these tools. Appreciate your patience.

# Payrails Product Assessment
Summary of Steps...
1. **Request Access Token**  
   Using client ID and API key to obtain a mock access token from Mockoon.

2. **Initialize Client SDK**  
   Fetched public key and holder reference from `/client/sdk`.

3. **Encrypt Card Details**  
   Used JWE (RSA-OAEP-256 + A256CBC-HS512) to encrypt test card data.

4. **Tokenize Card**  
   Sent encrypted payload to `/instruments` endpoint to simulate tokenization.

Tools I used...
- **Postman** — To manage and send API requests  
- **Mockoon** — To simulate Payrails backend API  
- **Online JWE Encryptor / Python** — To generate JWE encrypted payload
- **ChatGPT** — To guide me through the case study
