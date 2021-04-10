# How to get IP Address of your computer using Python

In this post we will learn How to get IP address of your computer in python.

You have to first import socket library and then use:

IP =socket.gethostbyname(hostname)

and then print the value of the ip into the print() function your IP address will be displayed as shown in the snippet.

```python
import socket
hostname = socket.gethostname()
IPAddr = socket.gethostbyname(hostname)

print("Your Computer Name is: " + hostname)
print("Your Computer IP Address is: " + IPAddr)
```

That’s all you need my friend. its that simple.
