# Double 85

To brute force all possible options
![image_11.png](image_11.png)

[CyberChef Link](https://gchq.github.io/CyberChef/#recipe=ROT47(47)ROT47_Brute_Force(200,0,true,'')Fork('%5C%5Cn','%5C%5Cn',false)Conditional_Jump('~%2B',false,'X',10)From_Base85('!-u',true,'z')Label('X')Merge(true)Filter('Line%20feed','mhs%7B',false)&input=OyVldjI0d2RUVj07IzknNlJ4ZzA2UDxiXjgxKw)

or

since we know it was encoded with 85 we just do the opposite

![image_12.png](image_12.png)
[CyberChef Link](https://gchq.github.io/CyberChef/#recipe=ROT47(-85)From_Base85('!-u',true,'z')&input=OyVldjI0d2RUVj07IzknNlJ4ZzA2UDxiXjgxKw)

```
mhs{W0W_this_wa5_hard}
```