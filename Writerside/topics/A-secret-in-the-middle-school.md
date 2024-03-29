# A secret in the middle school

Putting it through aperi and looking for the last string we find an encodded flag

![image_28.png](image_28.png)

Putting that in cyberchef and brute forcing some option shows the string

[CyberChef Link](https://gchq.github.io/CyberChef/#recipe=ROT13_Brute_Force(true,true,false,100,0,false,'')Filter('Line%20feed','mhs',false)&input=eXRle2kwaV9pMGl9)

![image_29.png](image_29.png)

```Python
mhs{w0w_w0w}
```