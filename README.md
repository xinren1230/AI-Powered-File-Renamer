# AI-Powered-File-Renamer
This Tkinter-based GUI application allows you to rename multiple files automatically using OpenAI’s GPT models. It can process text from various file types and generate smart, structured filenames based on content.


✅ Drag & Drop Support – Drop files directly into the GUI for renaming.

✅ Folder Selection – Choose a folder to rename all supported files at once.

✅ ChatGPT Model Selection – Choose between gpt-3.5-turbo, gpt-4o-mini, gpt-4, etc.

✅ Supports Multiple File Types:

Documents: .pdf, .doc, .docx, .ppt, .pptx, .xls, .xlsx
Scripts & Code: .txt, .py, .m, .ipynb

✅ Auto-Saving in Original Location – Files are renamed without moving.

✅ Unique Filenames – Prevents overwriting by appending an auto-incrementing counter.

✅ Live Output Log – Displays renaming process in a scrolling text window.


📌 Requirements

🔹 !!! Create an api_key.txt file in the same folder, which should include the OpenAIpenai API key.

🔹 Install dependencies before running:

pip install openai tiktoken tkinterdnd2 PyPDF2
(Python 3.8+ recommended)

🛠️ Usage
Create an api_key.txt file in the same directory as the script.

Inside the file, add your OpenAI API key (no quotes, just the key).
Run the script:

sh
Copy
Edit
python file_renamer.py
Select a ChatGPT Model from the dropdown.

Rename Files:

Drag & Drop files into the GUI.
Click "Select Folder" to rename all supported files in a folder.
Check Output Messages at the bottom of the GUI.

📄 Filename Formatting
🔹 OpenAI generates clean, structured filenames based on file content:

SCI Journal Papers → short_title_short_journal_publish_year.pdf

Books → Book_Title_Author_Year.pdf

Code Files → Project_Name_Version.py

If no content is detected, the filename format falls back to:
➡ empty_file_TIMESTAMP.extension

🎯 Example Workflow
Original File:
📄 random_file_1234.pdf

Extracted Content:

"Deep Learning for Image Recognition, published in IEEE Transactions on AI, 2023."

Renamed Output:
📄 deep_learning_ieee_2023.pdf

🚀 Future Enhancements
🔹 Support for additional file formats
🔹 Custom filename templates
🔹 Bulk renaming across multiple folders

📜 License
🔹 MIT License – Free to use and modify.

[![Demo Video](https://youtu.be/syGuh8p0T8Q/0.jpg)](https://youtu.be/syGuh8p0T8Q)
