# pyinstaller


C:\Python310\python -m venv venv
venv\Scripts\activate.bat
python.exe -m pip install --upgrade pip
pip install -r requirements.txt
pyinstaller -y --clean --additional-hooks-dir extra-hooks main.py --onefile


