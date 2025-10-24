# Google API KEY
AIzaSyBq98VzTOh-IPl8OCAL64Jm_oTKSvgcteg

https://generativelanguage.googleapis.com

![alt text](image-1.png)

docker run -d -p 3000:3000  -e OPENAI_API_KEY="AIzaSyBq98VzTOh-IPl8OCAL64Jm_oTKSvgcteg"  -e BASE_URL="https://generativelanguage.googleapis.com"  -e ENABLE_BALANCE_QUERY=1  -e CUSTOM_MODELS=-all,+gpt-3.5-turbo@openai=gpt-3.5-turbo,+gpt-4o@openai=gpt-4o,+gemini-pro@google=gemini-pro --name nextchat  ddayup/nextchat:latest  