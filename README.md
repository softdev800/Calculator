# Calculator
Приложения Калькулятор.

Initial setup:
pip3 install PyQt5
pip3 install -r requirements.txt
pyuic5 mainwindow.ui -o MainWindow.py

pip3 install PyInstaller
pip3 install PyQt5 PyInstaller
pyinstaller --windowed --icon=icons/calculation-128.ico --name Calculator calculator.py
