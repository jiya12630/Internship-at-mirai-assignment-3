# Internship-at-mirai-assignment-3


## 🤖 AI Multiverse Chat Studio
AI Multiverse Chat Studio is a premium, interactive Streamlit web application that lets you explore and converse with a wide range of unique AI personas across different languages. Powered by the next-generation Google Gemini API (gemini-2.5-flash model via the official google-genai SDK), it provides a dynamic interface tailored for a premium user experience.

<img width="1920" height="912" alt="chatbot_screenshot" src="https://github.com/user-attachments/assets/534171d5-04d5-46a2-985e-0d357069febd" />

<img width="1920" height="924" alt="chatbot_demo" src="https://github.com/user-attachments/assets/7db02509-2e2b-4684-a566-bfae1ddf72f4" />

## Features

- Multilingual Support: Choose to have the personas reply in English, Spanish, French, German, Portuguese, Hindi, Japanese, or Mandarin.
- Stateful Memory Vault: Seamless conversational context retention across turns using st.session_state. The chatbot remembers previous messages even when switching parameters or selected personas.
- Native Chat UI: Modern, interactive chat flow using Streamlit's native st.chat_input (with the walrus operator) and st.chat_message containers.
- Prompt Inspector: Dynamically inspect the structured system directive and profile instructions sent to Gemini before calling the API.
- Premium Aesthetics: Customized modern UI styling with vibrant glassmorphic gradients, clean typography, and a polished dashboard.

