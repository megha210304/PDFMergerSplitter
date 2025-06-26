📄 PDF Merger & Splitter — A Simple, Handy Python Tool
Hey there! 👋
This is a small project I built to solve a very real problem I kept running into — managing PDF files. Whether it’s merging tons of PDFs into one (hello, assignments!) or splitting out just a few pages from a big file, this tool gets it done easily — all from the terminal.
It’s built in Python using PyPDF2, and the goal was to make something clean, quick, and easy to use — no fuss, no fancy UI (yet 😅).
🔧 What It Can Do
Here’s what this tool helps you with:
🔗 Merge PDFs: Combine multiple PDF files in the order you want.
✂️ Split PDFs: Extract specific pages or ranges into new PDF files.
💾 Save Your Output: It lets you choose where to save and what to name your final PDF.
Right now, it’s CLI-based — so everything works through terminal prompts, but it’s clear, interactive, and beginner-friendly.
🧠 Why I Made This -
Honestly? I was tired of looking for online tools and uploading sensitive documents to random websites. So I thought — why not just build my own?
This project gave me hands-on experience with:
File handling in Python
Reading/writing PDFs using PyPDF2
Thinking like a user — not just a developer
And most importantly, it made me appreciate how useful small tools can be when built with care.
⚙️ How to Use It (Super Easy)
Clone the repo:
bash
git clone https://github.com/yourusername/pdf-merger-splitter.git
cd pdf-merger-splitter
Set up your environment:
bash
python -m venv venv
source venv/bin/activate  # (use venv\Scripts\activate on Windows)
Install the library:
bash
pip install PyPDF2
Run the app:
bash
python main.py
It’ll guide you from there — you just follow the prompts.

🚀 What I Want to Add Next-
A drag-and-drop GUI version (Tkinter maybe?)
Support for password-protected PDFs
Error messages that are more helpful (instead of scary Python ones 😅)
More flexibility like reordering pages before merging
