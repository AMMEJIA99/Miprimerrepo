import re

x= "python123"
y= re.findall('[a-z0-9]', x)
print(y)