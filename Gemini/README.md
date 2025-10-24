# Google API KEY
AIzaSyBq98VzTOh-IPl8OCAL64Jm_oTKSvgcteg

https://generativelanguage.googleapis.com

![alt text](image-1.png)



docker run -d -p 3000:3000  -e GOOGLE_API_KEY="AIzaSyBq98VzTOh-IPl8OCAL64Jm_oTKSvgcteg"  -e BASE_URL="https://generativelanguage.googleapis.com"  -e ENABLE_BALANCE_QUERY=1  -e CUSTOM_MODELS=+gemini-2.5-flash@google=gemini-2.5-flash --name nextchat  ddayup/nextchat:latest  