# vazifa-1
#Farruxbek uchun fork fayl


#
# import sys
from PyQt5.QtWidgets import QApplication, QWidget, QPushButton
i = 10
def kam():
    global i
    i = i - 1
    btn.setText(str(i))
    if i == 0:
        btn.setCheckable(False)
        btn.setDisabled(True)
app = QApplication([])
btn = QPushButton("10")
btn.clicked.connect(kam)
btn.show()
app.exec()

# i = 0
# def a():
#     global i
#     i += 1
#     print(i)
# app = QApplication([])
# btn = QPushButton("Press me")
# btn.clicked.connect(a)
# btn.show()
# app.exec()


