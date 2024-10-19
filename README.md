# SensoryBotLinux

![alt text](https://github.com/sensoryfox/SensoryBotLinuxoid/blob/master/HowItsLook.png?raw=true)

## SensoryBot: Your Personal AI Assistant in Telegram with File Management

SensoryBot is more than just a bot for interacting with LLM models through the Ollama API. It’s a full-fledged tool for managing your files, accessible both through Telegram and a user-friendly graphical interface.

**Key Features of SensoryBot:**

* **Local LLM Models:** Run powerful LLaMA models on your own computer, without relying on cloud services.
* **Convenient Interface:** Manage your bot and files through Telegram or with a GUI application built on PyQt6.
* **File Handling:** Send files (pdf, pptx, txt, xlsx, images) directly to the bot in Telegram or upload them via the GUI.
* **Built-in Parser:** SensoryBot automatically extracts text from PDF files, presentations, and images using pdfminer and Tesseract OCR.
* **File Management:** Store, organize, and manage all your files in one place.
* **Accessibility:** SensoryBot runs even on modest computers, successfully running llama2:3b-instruct-q6_K on a system with a GTX 1650 4GB graphics card.

**Installing SensoryBot on Linux:**

The installation process is as simple as possible:

1. **Clone the repository:**
```
git clone https://github.com/sensoryfox/SensoryBotLinuxoid.git
```
3. **Install dependencies:**
```
cd SensoryBotLinux
sudo apt install libarchive13 liblept5 poppler-utils
```
5. **Run the application:**
```
chmod +x *.sh *.py  # Configure permissions if necessary
./start.sh
```
7. **Connect the bot in Telegram:** find the bot by token and start interacting.

**Working with Files in SensoryBot:**

* **Sending files in Telegram:** simply send the file to the bot chat as if you were sending it to another user.
* **Uploading files via the GUI:** use the intuitive application interface to upload files from your computer.
* **Processing and analysis:** SensoryBot automatically extracts text from files, prepares it for the LLM model, and provides you with relevant information.
* **Storage and management:** all your files are stored in a special repository, which you can access both through Telegram and through the GUI.

**SensoryBot is a powerful tool for working with information that opens up new horizons for interacting with artificial intelligence.** 
