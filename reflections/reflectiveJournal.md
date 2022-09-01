# Reflective Journal

## Week 1:


### What is Scratch?
Scratch is a high-level block-based programming language and website.
### What is visual programming?
Visual programming lets users create programs by manipulating program elements graphically rather than by specifying them textually.
### What are some programming principles that you have discovered?
One of the principles of programming I have learned is to keep code simple. Generally, the more simple and clear the code, the better. It is easier to work with, and easier for other people to read. Also known as K.I.S.S (Keep it simple, stupid). In one of the first lectures I attended, Roman mentioned D.R.Y (Don't repeat yourself). Though I have little experience with coding so far, this principle makes sense and seems to relate to K.I.S.S. Duplication of data, logic, or function in code not only makes your code lengthy but also wastes a lot of time when it comes to maintaining, debugging or modifying the code. If you need to make a small change in your code then you need to do it at several places. D.R.Y. aims to reduce the repetition of code. It states that a piece of code should be implemented in just one place in the source code. When looking into this, I found it funny to learn that the opposite of the D.R.Y. principle is W.E.T.: “write everything twice” or “waste everyone's time".
### Can you share your favourite Scratch project that you have made or remixed?
[Here](https://scratch.mit.edu/projects/717595495/) is a basic pong game.


## Week 2:

### What is git?
Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.
### What is GitHub?
GitHub is an Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project.


## Week 3 Python tasks:

### Activity 1
#### Write a Python program that calculates a dog's age in dog's years.

age = float(input("How old is your dog in human years? "))
if age == 2:
    print("Your dog is", 10.5, "years old")
elif age > 2:
    print("Your dog is", (age-2)*4 + 21, "years old")
elif age <= 1:
    print("your dog is a puppy")
elif age >1 and age <2:
    print("your dog is an adolescent")
    
**_-Note: I worked on this code with a class mate._**


### Activity 2 
#### Write a Python program to convert month name to a number of days.

month = input("Which month would you like to know the length of? ")
if month == "January" or month == "March" or month == "May" or month == "July" or month == "August" or month == "October" or month == "December":
    print("There are 31 days in",month + ".")
elif month == "April" or month == "June" or month == "September" or month == "November":
    print("There are 30 days in",month + ".")
elif month == "February":
    print("There are 28 days in February, or 29 days on a leap year.")
   
**_-Note: While this code ulitmately gets the job done, it is a very long and drawn out way to write it! I'd like to practice with lists. I am still proud of myself for having come up with a working code off the top of my head, though :)_**

**_-Note: I asked a peer who is more knowledgeable about python, and they helped me get a better understanding of lists. While they're both about the same length, I think this code is a bit more clear:_**

month_31 =['January','March', 'May', 'July', 'August', 'October', 'December']
month_28_29 =['February']
month_30 =['April', 'June', 'September', 'November']
birth_month= input("Which month would you like to know the length of? ")
if birth_month in month_31:
    print("There are 31 days in",birth_month + ".")
elif birth_month in month_30:
    print("There are 30 days in",birth_month + ".")
elif birth_month in month_28_29:
    print("There are 28 days in February, or 29 days on a leap year.")


### Activity 3
#### Write a Python program to check a string represent an integer or not.

text = input("Input a string: ")

if text.isdigit():
    print("The string is an integer.")

else:
    print("The string is not an integer.")

**_-Note: I was pleasantly surprised with how easy this one was! I had a little read up on canvas and saw this ".isdigit" function. With a little trial and error, I was able to write a nice, short code that gets the job done._**


### Activity 4
#### Write a Python program that ask user to input two numbers. Check if both numbers are divisible by 2 or 3, if yes multiply them and print them on screen. If not, add them and then print it on screen. 

num_1= int(input("Enter first number: "))
num_2= int(input("Enter second number "))
if num_1 % 2 ==0 or num_1 % 3 == 0 and num_2 % 2 == 0 or num_2 % 3 ==0:
    print(num_1 * num_2 )

**_-Note: Another short and sweet one! I find that creating a successful code, no matter how simple, is very satisfying and boosts my coding confidence._**


### Activity 5
#### Write a menu driven Python program that give user options to perform temperature conversion. Your code should be able to convert temperature from Celsius to Fahrenheit and vice versa.

temp = input("Enter '1' to convert Celsius to Fahrenheit\nEnter '2' to convert Fahrenheit to Celsius\nEnter '3' to quit: ")
if "1" in temp:
    celsius = float(input("Enter the temperature in Celsius: "))
    fahrenheit = celsius*1.8+32
    print(str(celsius) + "° celsius is equivalent to " + str(fahrenheit) + "° fahrenheit")
elif "2" in temp:
    fahrenheit = float(input("Enter the temperature in Fahrenheit: "))
    celsius = ((fahrenheit - 32) *5 / 9)
    print(str(fahrenheit) + "° Fahrenheit is equivalent to", str(celsius) + "° Celsius")
    
**_-Note: Another satisfying code! I can be quite a meticulous person, so I really enjoyed combing out the finer (potentially unnecessary) details, for example: The comma in python creates a space, whereas the '+' does not! When I added in the '°' symbol, in all the places where I have the '+', initially I had a comma. I didn't want there to be a space between the integer and the '°' (e.g. 30° not 30 °). However, when I changed this, it gave me back an error!! It then took me a minute to realize that I needed to put the 'str' function in front of the integers as Python was trying to read it like an equation._**

**_-Note: Although I have added in the option "Enter '3' to quit", I am still unsure as to how to do this! I will be looking into it._**


**_-Note: I've found it so interesting to learn these codes! Even though they are simple, it's fascinating to learn the "behind the scenes" of, for example, a web page. Having used computers for the majority of my life, I've never really questioned how computing actually works. I may not be articualting myself in the clearest way, but when doing these exercises and some self-directed study, I constantly find myself thinking "Ohhh, that's how it's done!"._**


## Week 4: Python activities continued

### Activity 6
#### Write a Python program that takes distance and time as input and displays the speed in: meters per second, kilometers per hour, and miles per hour.


## Week 5:

Agile.


## Week 6:

### Prompts

#### Did you remember to take regular breaks away from your screen during this week? How often? Did you stretch your body?
To be quite honest, I don't think forgetting to take breaks is an issue for me. While I'm not proud of it and need to work on it, for as long as I can remember I have always been a procrastinator! I am somewhat time-blind, and the importance of getting tasks done only becomes apparent to me as the deadline closes in!

#### What is Timeboxing? Have you heard of it before? Will you use it?

#### On a a 0-5 scale, how confident are you with each of the assignments?

#### What are of you proud of up to this point in the course?

#### Do you have a personal learning strategy? If so, what parts of your learning strategy worked? What problems did you face? If you don't have a personal strategy yet, what do you think might work? Invent a describe a strategy for yourself. 


#### If you could send a time traveling text message back to yourself at the start of this course, what would it say?

#### What is Python?

#### Have you developed a habit of exploring?

#### Have you meditated before?

#### Is there something over which you have gained a degree of mastery before in your life? Gymnastics, Rubik's Cubes, A Video Game? What did it take?

#### Do you consider yourself a developer yet?

#### Do you value creativity? As a value itself? What about as a tool for learning to think logically?

#### How many tabs do you have open in your web browser right now? What is the ratio of study related tabs to distraction related tabs?

#### Have you had a fight response to technology? What does it feel like? How did you overcome this?

#### What is an IDE?

#### What did you learn out of the Marshmallow Challenge?

#### Did you have any blocks during this challenge? How did you overcome them?

#### So far, what was the hardest moment of this course for you?

#### What is OOP?

#### Are you using the canvas content? Do you find it helpful or tedious?

#### Which parts of the work did you find tedious?

#### What is polymorphism?

#### Did you hear a self critical voice in your head throughout the process of learning during this last few weeks? What did it say to you? Do you believe what it said?

#### What is an MVP? How would you describe it to a group of 6 year olds?

#### What is the hardest problem you have solved so far?

#### What is pair programming?

#### What are you looking forward to learning about programming?

#### What is conscious listening?

#### What is a variable?

#### What programming languages are you interested in learning? Why?

#### What is something kind that someone has done for you?

#### If you were describing programming to someone who knows nothing about it, what would you say?

#### Which parts of this course made you feel doubtful of your own innate ability?

#### What is a fixed mindset?

#### What is something kind you have done for someone else?

#### Have you done mindfulness or attention training before?

#### Have you developed a habit of persevering?

