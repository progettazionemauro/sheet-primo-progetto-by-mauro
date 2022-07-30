26/07/22 - IL TUTTO FUNZIONA! 

1) sudo apt-get install python3-pip
2) pip3 install pipenv
3) cd myproject
4) python3 -m venv env e poi source env/bin/activate
5) pip3 install gsheetsdb
5 . a) se è presente requirements.txt installare e duenque: pip3 install -r requirements.txt
6) streamlit hello
6.a) nel caso non si sia creato il gitignore git init potrebbe dare un errore di overflow per cui rimuovere il file con rm -rf .git
6. b) creare il file .gitignore ed inserire venv
6.c) creare .streamlit/secrets.toml
6. d) inserire il format seguente come # SPREADSHEET_ID = "1Y6_89ick_tTQeVh4OGP44pXOrexZw1ASnlES8-s_1zY"
7) git init


Strutturare la repository con git
7) creare nella root il file .gitignore ed inserire 

Vedere aqui: https://github.com/streamlit/streamlit


Google Sheet:
Vedere qui: https://shritam.medium.com/google-sheets-a-database-c4e3fef6e0bc
1) pip3 install gspread oauth2client gsheetsdb


7) streamlit run myfile.py

PROVA PULL
