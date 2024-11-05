# Npc-Generator-Project

## Features

- Feature 1: My program takes the user input on gender and creates a character with atributes specific for that gender
- Feature 2: My program is very concise working in under forty lines saving time and data for the user
  
## Overview

My code is a python progrom used to create "random" characters for a
[Screen recording 2024-11-05 8.04.13 AM.webm](https://github.com/user-attachments/assets/14f7ab63-a409-43ea-9900-838104ba5ba8)

## Code Example

```python
if gender == "male":
        print("Their name is ",mfirstname[random.randint(0, 129)] + " " + lastnames[random.randint(0, 126)])
        print("Their age is ",age[random.randint(0,99)]," years old")
        print("Their iq is ",iq[random.randint(0,179)])
        print("Their ethnicity is ",ethnicity[random.randint(0,221)])
        print("They are ",height[random.randint(0,28)]," feet tall\n")
    elif gender == "female":
        print("Their name is ",ffirstname[random.randint(0, 107)] + " " + lastnames[random.randint(0, 126)])
        print("Their age is ",age[random.randint(0,99)]," years old")
        print("Their iq is ",iq[random.randint(0,179)])
        print("Their ethnicity is ",ethnicity[random.randint(0,221)])
        print("They are ",height[random.randint(0,28)]," feet tall\n")
