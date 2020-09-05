# QR-Code-Scanner
pip install pyqrcode
>>>  sudo apt-get install  
     python-qrtools
import qrtools
>>> qr = qrtools.QR()
>>> qr.decode("image.png") 
>>> print qr.data
