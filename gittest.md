# gittest

1. 项目1
2. 项目2
3. 项目3-1
4. ~~项目4~~  

git ssh搞好了


<battle.net>  
Diablo II [战网](https://battle.net)

下面是一段PY代码

环境信息

操作系统:windows 10

终端:Windows PowerShell

```python
import serial


class DCPower:

    def DC_ON(self):
        # ser=serial.Serial('COM6',9600,timeout=0.5)
        self.ser.read(b'OUT\n')
        B = self.ser.read(1000)
        print(B)
        self.ser.close()
        return

    def __init__(self):
        self.ser = serial.Serial('COM3', 9600, timeout=0.5)


a = DCPower()
a.DC_ON()

```
