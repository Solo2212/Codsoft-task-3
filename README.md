# Codsoft-task-3
A password generator is a useful tool that generates strong and random passwords for users. This project aims to create a password generator application using Python, allowing users to specify the length and complexity of the password

import string
import random
s1=string.ascii_letters

s2=string.punctuation

s3=string.digits

plen=int(input("Enter the length of password:  "))



l=[]
l.extend(list(s1))
l.extend(list(s2))
l.extend(list(s3))


random.shuffle(l)

print("your password is: ")


print("".join(l[0:plen]))
.
