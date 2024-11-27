# Password-Generator

import string
import random

def generate_password(length=12)
	#Define the character set: Letter, Digits and Punctuation
	Characters = string.ascii_letters + string.digits + string.punctuations
	#Generate a random password using the character set
	password = ''.join(random.choice(characters)for _ in range(length))
	
	return password

	
#Generate a password and print it
new_password = generate_password()
print(f"Generated Password : {new_password}")
	     

