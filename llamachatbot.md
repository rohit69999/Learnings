# Learnings
Keeping Track of the Learnings 
##chatbot with llama
##A screenshot from Hugging Face showing access
<img width="1440" alt="Screenshot 2024-11-28 at 11 03 22 AM" src="https://github.com/user-attachments/assets/e9797f5b-9f23-4262-a638-4c3c49ad42c9">
##A screenshot of the downloaded local files using ls -al 
<img width="915" alt="Screenshot 2024-11-28 at 11 09 00 AM" src="https://github.com/user-attachments/assets/ac3e3974-18c1-492a-bd1c-397297bd6dc9">
##Find the appropriate download link of Q5_K_M quantitized Phi-3 mini model from Microsoft.
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/bce8b4ba-84fc-4c26-b4ad-5230c3b93396">
##link to download the model
https://huggingface.co/microsoft/Phi-3-mini-4k-instruct-gguf/resolve/main/Phi-3-mini-4k-instruct-q4.gguf?download=true

<img width="1419" alt="Screenshot 2024-11-28 at 11 45 49 AM" src="https://github.com/user-attachments/assets/6fbd8768-a7c5-4862-9b74-db492ba7aeb8">

<img width="1440" alt="Screenshot 2024-11-28 at 12 34 57 PM" src="https://github.com/user-attachments/assets/e039ece6-d8ec-43ab-818c-ded20643f283">

###Command is  wasmedge --dir .:.   --nn-preload default:GGML:AUTO:Phi-3-mini-4k-instruct-q4.gguf   llama-chat.wasm   --prompt-template llama-3-chat   --system-prompt "You are a high school physics teacher. Explain about laws of motion"##

##command curl ##-X POST http://localhost:8080/v1/chat/completions \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{"messages":[{"role":"system", "content": "You are a high school physics teacher. Explain about laws of motion"}, {"role":"user", "content": "What is newtons first law?"}]}'##
  <img width="1434" alt="Screenshot 2024-11-28 at 1 12 06 PM" src="https://github.com/user-attachments/assets/deafe8e5-bc16-4748-a94d-b02fffcb6867">


##configuring the sysytem prompt##

<img width="1440" alt="Screenshot 2024-11-28 at 1 16 04 PM" src="https://github.com/user-attachments/assets/d59a07c2-9200-452a-b445-76b25c5f5895">










