Bundle RFT to TXT converting using Mac Terminal

find . -name directory\*.rtf -print0 | xargs -0 textutil -convert txt
