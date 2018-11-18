print('"asma\'s world"')
msg = """hello every one  
my name is asma"""            # """ this is fro multiple lines"""
print(msg)
print(len(msg))               # len for quantity of letters includeing spaces
print(msg[5:11])
print(msg.lower())
print(msg.upper()) 
print(msg.count("m"))         # count the letters in string
print(msg.find("asma"))         # finding the location 
msg1 = msg.replace("asma" , "zahra")
msg = msg1
print(msg)
...................................................................................................................
"asma's world"
hello every one  
my name is asma
33
 every
hello every one  
my name is asma
HELLO EVERY ONE  
MY NAME IS ASMA
3
29
hello every one  
my name is zahra
........................................................................................................

greeting = "hello"
name = "asma"
msg3 = greeting +  ", " + name
print(msg3)

hello, asma
........................................................................................................
msg3 = "{}, {}. welcome!".format(greeting, name)
print(msg3)

hello, asma. welcome!
.........................................................................................................
msg3 = f"{greeting.lower()} , {name.upper()}. welcome!"
print(msg3)

hello , ASMA. welcome!
.........................................................................................................
print("%s, %s. Welcome!" %(greeting,name))

hello, asma. Welcome!
........................................................................................................


