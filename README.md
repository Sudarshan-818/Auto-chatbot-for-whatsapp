I have created an auto-reply WhatsApp chatbot that reads the latest incoming message from WhatsApp Web using PyAutoGUI (mouse/keyboard automation)
and Pyperclip (clipboard copy-paste). The script checks if the last message is from a specific sender, sends that message to Groq’s LLaMA 3 model
with a custom persona prompt, receives a relevant, human-like reply, and automatically pastes andsends it back in WhatsApp. You fine-tuned prompts, 
improved response formatting, adjusted screencoordinates for accurate automation, and added checks to avoid replying unnecessarily.

Manual:
--> Login you whatsapp account on browser and put it somewhere on taskbar
--> Place Chrome(whatsapp) icon in taskbar (preferably first icon).
-->The bot will:
    > Click WhatsApp Web tab
    > search name of someone we want to set our bot
    > open his chat
    > Copy the latest message
    > Send it to the AI for response
    > Paste and send the reply automatically
    > wait for sender's response does the same process
