# Secure E2EE Chat

End-to-end encrypted real-time chat with zero-knowledge file sharing.

## Features

• AES-256-GCM client-side encryption  
• No login system  
• Encrypted file sharing  
• WebSocket real-time transport  
• Auto-destructing rooms  
• Zero server plaintext access  

## Run locally

```bash
pip install -r requirements.txt
uvicorn main:app --reload
