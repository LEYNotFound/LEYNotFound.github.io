# LEYNotFound
### LEYNotFound.github.io

[Kill JiYu](https://wwub.lanzoue.com/b04wg7d2f)
```
# -*- coding: utf-8 -*-

# Form implementation generated from reading ui file 'untitled.ui'
#
# Created by: PyQt5 UI code generator 5.15.9
#
# WARNING: Any manual changes made to this file will be lost when pyuic5 is
# run again.  Do not edit this file unless you know what you are doing.


from PyQt5 import QtCore, QtGui, QtWidgets
import random
class Ui_MainWindow(object):
    def setupUi(self, MainWindow):
        MainWindow.setObjectName("MainWindow")
        MainWindow.setEnabled(True)
        MainWindow.resize(1920, 1080)
        MainWindow.setLayoutDirection(QtCore.Qt.LeftToRight)
        MainWindow.setToolButtonStyle(QtCore.Qt.ToolButtonIconOnly)
        MainWindow.setTabShape(QtWidgets.QTabWidget.Rounded)
        self.centralwidget = QtWidgets.QWidget(MainWindow)
        self.centralwidget.setObjectName("centralwidget")
        self.lcdNumber = QtWidgets.QLCDNumber(self.centralwidget)
        self.lcdNumber.setEnabled(True)
        self.lcdNumber.setGeometry(QtCore.QRect(10, 240, 300, 300))
        font = QtGui.QFont()
        font.setFamily("Arial")
        font.setPointSize(6)
        self.lcdNumber.setFont(font)
        self.lcdNumber.setMouseTracking(False)
        self.lcdNumber.setTabletTracking(False)
        self.lcdNumber.setFrameShape(QtWidgets.QFrame.NoFrame)
        self.lcdNumber.setFrameShadow(QtWidgets.QFrame.Plain)
        self.lcdNumber.setLineWidth(1)
        self.lcdNumber.setMidLineWidth(0)
        self.lcdNumber.setSmallDecimalPoint(False)
        self.lcdNumber.setDigitCount(2)
        self.lcdNumber.setMode(QtWidgets.QLCDNumber.Dec)
        self.lcdNumber.setSegmentStyle(QtWidgets.QLCDNumber.Filled)
        self.lcdNumber.setProperty("value", 88.0)
        self.lcdNumber.setProperty("intValue", 88)
        self.lcdNumber.setObjectName("lcdNumber")
        self.label = QtWidgets.QLabel(self.centralwidget)
        self.label.setGeometry(QtCore.QRect(10, 610, 300, 150))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        font.setBold(True)
        font.setWeight(75)
        self.label.setFont(font)
        self.label.setFrameShape(QtWidgets.QFrame.Box)
        self.label.setTextFormat(QtCore.Qt.MarkdownText)
        self.label.setAlignment(QtCore.Qt.AlignCenter)
        self.label.setObjectName("label")
        self.lcdNumber_2 = QtWidgets.QLCDNumber(self.centralwidget)
        self.lcdNumber_2.setEnabled(True)
        self.lcdNumber_2.setGeometry(QtCore.QRect(330, 240, 300, 300))
        font = QtGui.QFont()
        font.setFamily("Arial")
        font.setPointSize(6)
        self.lcdNumber_2.setFont(font)
        self.lcdNumber_2.setMouseTracking(False)
        self.lcdNumber_2.setTabletTracking(False)
        self.lcdNumber_2.setFrameShape(QtWidgets.QFrame.NoFrame)
        self.lcdNumber_2.setFrameShadow(QtWidgets.QFrame.Plain)
        self.lcdNumber_2.setLineWidth(1)
        self.lcdNumber_2.setMidLineWidth(0)
        self.lcdNumber_2.setSmallDecimalPoint(False)
        self.lcdNumber_2.setDigitCount(2)
        self.lcdNumber_2.setMode(QtWidgets.QLCDNumber.Dec)
        self.lcdNumber_2.setSegmentStyle(QtWidgets.QLCDNumber.Filled)
        self.lcdNumber_2.setProperty("value", 88.0)
        self.lcdNumber_2.setProperty("intValue", 88)
        self.lcdNumber_2.setObjectName("lcdNumber_2")
        self.label_2 = QtWidgets.QLabel(self.centralwidget)
        self.label_2.setGeometry(QtCore.QRect(330, 610, 300, 150))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        font.setBold(True)
        font.setWeight(75)
        self.label_2.setFont(font)
        self.label_2.setFrameShape(QtWidgets.QFrame.Box)
        self.label_2.setTextFormat(QtCore.Qt.MarkdownText)
        self.label_2.setAlignment(QtCore.Qt.AlignCenter)
        self.label_2.setObjectName("label_2")
        self.label_3 = QtWidgets.QLabel(self.centralwidget)
        self.label_3.setGeometry(QtCore.QRect(650, 610, 300, 150))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        font.setBold(True)
        font.setWeight(75)
        self.label_3.setFont(font)
        self.label_3.setFrameShape(QtWidgets.QFrame.Box)
        self.label_3.setTextFormat(QtCore.Qt.MarkdownText)
        self.label_3.setAlignment(QtCore.Qt.AlignCenter)
        self.label_3.setObjectName("label_3")
        self.lcdNumber_3 = QtWidgets.QLCDNumber(self.centralwidget)
        self.lcdNumber_3.setEnabled(True)
        self.lcdNumber_3.setGeometry(QtCore.QRect(650, 240, 300, 300))
        font = QtGui.QFont()
        font.setFamily("Arial")
        font.setPointSize(6)
        self.lcdNumber_3.setFont(font)
        self.lcdNumber_3.setMouseTracking(False)
        self.lcdNumber_3.setTabletTracking(False)
        self.lcdNumber_3.setFrameShape(QtWidgets.QFrame.NoFrame)
        self.lcdNumber_3.setFrameShadow(QtWidgets.QFrame.Plain)
        self.lcdNumber_3.setLineWidth(1)
        self.lcdNumber_3.setMidLineWidth(0)
        self.lcdNumber_3.setSmallDecimalPoint(False)
        self.lcdNumber_3.setDigitCount(2)
        self.lcdNumber_3.setMode(QtWidgets.QLCDNumber.Dec)
        self.lcdNumber_3.setSegmentStyle(QtWidgets.QLCDNumber.Filled)
        self.lcdNumber_3.setProperty("value", 88.0)
        self.lcdNumber_3.setProperty("intValue", 88)
        self.lcdNumber_3.setObjectName("lcdNumber_3")
        self.label_4 = QtWidgets.QLabel(self.centralwidget)
        self.label_4.setGeometry(QtCore.QRect(970, 610, 300, 150))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        font.setBold(True)
        font.setWeight(75)
        self.label_4.setFont(font)
        self.label_4.setFrameShape(QtWidgets.QFrame.Box)
        self.label_4.setTextFormat(QtCore.Qt.MarkdownText)
        self.label_4.setAlignment(QtCore.Qt.AlignCenter)
        self.label_4.setObjectName("label_4")
        self.lcdNumber_4 = QtWidgets.QLCDNumber(self.centralwidget)
        self.lcdNumber_4.setEnabled(True)
        self.lcdNumber_4.setGeometry(QtCore.QRect(970, 240, 300, 300))
        font = QtGui.QFont()
        font.setFamily("Arial")
        font.setPointSize(6)
        self.lcdNumber_4.setFont(font)
        self.lcdNumber_4.setMouseTracking(False)
        self.lcdNumber_4.setTabletTracking(False)
        self.lcdNumber_4.setFrameShape(QtWidgets.QFrame.NoFrame)
        self.lcdNumber_4.setFrameShadow(QtWidgets.QFrame.Plain)
        self.lcdNumber_4.setLineWidth(1)
        self.lcdNumber_4.setMidLineWidth(0)
        self.lcdNumber_4.setSmallDecimalPoint(False)
        self.lcdNumber_4.setDigitCount(2)
        self.lcdNumber_4.setMode(QtWidgets.QLCDNumber.Dec)
        self.lcdNumber_4.setSegmentStyle(QtWidgets.QLCDNumber.Filled)
        self.lcdNumber_4.setProperty("value", 88.0)
        self.lcdNumber_4.setProperty("intValue", 88)
        self.lcdNumber_4.setObjectName("lcdNumber_4")
        self.lcdNumber_5 = QtWidgets.QLCDNumber(self.centralwidget)
        self.lcdNumber_5.setEnabled(True)
        self.lcdNumber_5.setGeometry(QtCore.QRect(1290, 240, 300, 300))
        font = QtGui.QFont()
        font.setFamily("Arial")
        font.setPointSize(6)
        self.lcdNumber_5.setFont(font)
        self.lcdNumber_5.setMouseTracking(False)
        self.lcdNumber_5.setTabletTracking(False)
        self.lcdNumber_5.setFrameShape(QtWidgets.QFrame.NoFrame)
        self.lcdNumber_5.setFrameShadow(QtWidgets.QFrame.Plain)
        self.lcdNumber_5.setLineWidth(1)
        self.lcdNumber_5.setMidLineWidth(0)
        self.lcdNumber_5.setSmallDecimalPoint(False)
        self.lcdNumber_5.setDigitCount(2)
        self.lcdNumber_5.setMode(QtWidgets.QLCDNumber.Dec)
        self.lcdNumber_5.setSegmentStyle(QtWidgets.QLCDNumber.Filled)
        self.lcdNumber_5.setProperty("value", 88.0)
        self.lcdNumber_5.setProperty("intValue", 88)
        self.lcdNumber_5.setObjectName("lcdNumber_5")
        self.label_5 = QtWidgets.QLabel(self.centralwidget)
        self.label_5.setGeometry(QtCore.QRect(1290, 610, 300, 150))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        font.setBold(True)
        font.setWeight(75)
        self.label_5.setFont(font)
        self.label_5.setFrameShape(QtWidgets.QFrame.Box)
        self.label_5.setTextFormat(QtCore.Qt.MarkdownText)
        self.label_5.setAlignment(QtCore.Qt.AlignCenter)
        self.label_5.setObjectName("label_5")
        self.label_6 = QtWidgets.QLabel(self.centralwidget)
        self.label_6.setGeometry(QtCore.QRect(1610, 610, 300, 150))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        font.setBold(True)
        font.setWeight(36)
        self.label_6.setFont(font)
        self.label_6.setFrameShape(QtWidgets.QFrame.Box)
        self.label_6.setTextFormat(QtCore.Qt.MarkdownText)
        self.label_6.setAlignment(QtCore.Qt.AlignCenter)
        self.label_6.setObjectName("label_6")
        self.label_7 = QtWidgets.QLabel(self.centralwidget)
        self.label_7.setGeometry(QtCore.QRect(1610, 240, 300, 300))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        self.label_7.setFont(font)
        self.label_7.setObjectName("label_7")
        self.pushButton_6 = QtWidgets.QPushButton(self.centralwidget)
        self.pushButton_6.setGeometry(QtCore.QRect(1670, 800, 180, 80))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        self.pushButton_6.setFont(font)
        self.pushButton_6.setObjectName("pushButton_6")
        self.pushButton_7 = QtWidgets.QPushButton(self.centralwidget)
        self.pushButton_7.setGeometry(QtCore.QRect(1350, 800, 180, 80))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        self.pushButton_7.setFont(font)
        self.pushButton_7.setObjectName("pushButton_7")
        self.pushButton_8 = QtWidgets.QPushButton(self.centralwidget)
        self.pushButton_8.setGeometry(QtCore.QRect(1030, 800, 180, 80))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        self.pushButton_8.setFont(font)
        self.pushButton_8.setObjectName("pushButton_8")
        self.pushButton_9 = QtWidgets.QPushButton(self.centralwidget)
        self.pushButton_9.setGeometry(QtCore.QRect(710, 800, 180, 80))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        self.pushButton_9.setFont(font)
        self.pushButton_9.setObjectName("pushButton_9")
        self.pushButton_10 = QtWidgets.QPushButton(self.centralwidget)
        self.pushButton_10.setGeometry(QtCore.QRect(390, 800, 180, 80))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        self.pushButton_10.setFont(font)
        self.pushButton_10.setObjectName("pushButton_10")
        self.pushButton_11 = QtWidgets.QPushButton(self.centralwidget)
        self.pushButton_11.setGeometry(QtCore.QRect(70, 800, 180, 80))
        font = QtGui.QFont()
        font.setFamily("微软雅黑")
        font.setPointSize(36)
        self.pushButton_11.setFont(font)
        self.pushButton_11.setObjectName("pushButton_11")
        self.pushButton_11.raise_()
        self.pushButton_10.raise_()
        self.pushButton_9.raise_()
        self.pushButton_8.raise_()
        self.pushButton_7.raise_()
        self.lcdNumber.raise_()
        self.label.raise_()
        self.lcdNumber_2.raise_()
        self.label_2.raise_()
        self.label_3.raise_()
        self.lcdNumber_3.raise_()
        self.label_4.raise_()
        self.lcdNumber_4.raise_()
        self.lcdNumber_5.raise_()
        self.label_5.raise_()
        self.label_6.raise_()
        self.label_7.raise_()
        self.pushButton_6.raise_()
        MainWindow.setCentralWidget(self.centralwidget)
        self.statusbar = QtWidgets.QStatusBar(MainWindow)
        self.statusbar.setObjectName("statusbar")
        MainWindow.setStatusBar(self.statusbar)

        self.retranslateUi(MainWindow)
        self.pushButton_11.clicked.connect(self.l1c) # type: ignore
        self.pushButton_10.clicked.connect(self.l2c) # type: ignore
        self.pushButton_9.clicked.connect(self.l3c) # type: ignore
        self.pushButton_8.clicked.connect(self.l4c) # type: ignore
        self.pushButton_7.clicked.connect(self.l5c) # type: ignore
        self.pushButton_6.clicked.connect(self.l7c) # type: ignore
        QtCore.QMetaObject.connectSlotsByName(MainWindow)

    def retranslateUi(self, MainWindow):
        _translate = QtCore.QCoreApplication.translate
        MainWindow.setWindowTitle(_translate("MainWindow", "MainWindow"))
        self.lcdNumber.setWhatsThis(_translate("MainWindow", "<html><head/><body><p><br/></p></body></html>"))
        self.label.setText(_translate("MainWindow", "一等奖"))
        self.lcdNumber_2.setWhatsThis(_translate("MainWindow", "<html><head/><body><p><br/></p></body></html>"))
        self.label_2.setText(_translate("MainWindow", "二等奖"))
        self.label_3.setText(_translate("MainWindow", "二等奖"))
        self.lcdNumber_3.setWhatsThis(_translate("MainWindow", "<html><head/><body><p><br/></p></body></html>"))
        self.label_4.setText(_translate("MainWindow", "三等奖"))
        self.lcdNumber_4.setWhatsThis(_translate("MainWindow", "<html><head/><body><p><br/></p></body></html>"))
        self.lcdNumber_5.setWhatsThis(_translate("MainWindow", "<html><head/><body><p><br/></p></body></html>"))
        self.label_5.setText(_translate("MainWindow", "三等奖"))
        self.label_6.setText(_translate("MainWindow", "小惩罚"))
        self.label_7.setText(_translate("MainWindow", "??????"))
        self.pushButton_6.setText(_translate("MainWindow", "抽！"))
        self.pushButton_7.setText(_translate("MainWindow", "抽！"))
        self.pushButton_8.setText(_translate("MainWindow", "抽！"))
        self.pushButton_9.setText(_translate("MainWindow", "抽！"))
        self.pushButton_10.setText(_translate("MainWindow", "抽！"))
        self.pushButton_11.setText(_translate("MainWindow", "抽！"))


    def l1c(self,MainWindow):
        tn = random.randint(1, 49)
        self.lcdNumber.setProperty("intValue", tn)
    def l2c(self,MainWindow):
        tn = random.randint(1, 49)
        self.lcdNumber_2.setProperty("intValue", tn)
    def l3c(self,MainWindow):
        tn = random.randint(1, 49)
        self.lcdNumber_3.setProperty("intValue", tn)
    def l4c(self,MainWindow):
        tn = random.randint(1, 49)
        self.lcdNumber_4.setProperty("intValue", tn)

    def l5c(self,MainWindow):
        tn=random.randint(1,49)
        self.lcdNumber_5.setProperty("intValue", tn)

    def l7c(self,MainWindow):
        _translate = QtCore.QCoreApplication.translate
        self.label_7.setText(_translate("MainWindow", "舒老师"))

import sys
if __name__ == '__main__':
    app = QtWidgets.QApplication(sys.argv)
    MainWindow = QtWidgets.QMainWindow()
    ui = Ui_MainWindow()
    ui.setupUi(MainWindow)
    MainWindow.show()
    sys.exit(app.exec_())

```
