# Reflective Journal

_I hope you don't mind my use of symbols throughout this journal. If it were a physical journal of mine, it would have much more embellishments! I'm very fond of making things visually appealing._

## 🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮🌸 Week 1 🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮

### What is Scratch?
Scratch is a high-level block-based programming language and website.
### What is visual programming?
Visual programming lets users create programs by manipulating program elements graphically rather than by specifying them textually.
### What are some programming principles that you have discovered?
One of the principles of programming I have learned is to keep code simple. Generally, the more simple and clear the code, the better. It is easier to work with, and easier for other people to read. Also known as K.I.S.S (Keep it simple, stupid). In one of the first lectures I attended, Roman mentioned D.R.Y (Don't repeat yourself). Though I have little experience with coding so far, this principle makes sense and seems to relate to K.I.S.S. Duplication of data, logic, or function in code not only makes your code lengthy but also wastes a lot of time when it comes to maintaining, debugging or modifying the code. If you need to make a small change in your code then you need to do it at several places. D.R.Y. aims to reduce the repetition of code. It states that a piece of code should be implemented in just one place in the source code. When looking into this, I found it funny to learn that the opposite of the D.R.Y. principle is W.E.T.: “write everything twice” or “waste everyone's time".
### Can you share your favourite Scratch project that you have made or remixed?
[Here](https://scratch.mit.edu/projects/717595495/) is a basic pong game.


## 🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮🌸 Week 2 🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮

### What is git?
Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.
### What is GitHub?
GitHub is an Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project.


## 🌸💮🌸💮🌸💮🌸💮🌸💮🌸 Week 3: Python tasks 🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮
                         
### Activity 1
* **Write a Python program that calculates a dog's age in dog's years.**

You can find this code [here.](https://github.com/LordFuzzBear/LabActivities/blob/master/Lab%20Activity%201.py)
    
**_-Note: I worked on this code with a class mate._**

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

### Activity 2 
* **Write a Python program to convert month name to a number of days.**

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

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

### Activity 3
* **Write a Python program to check a string represent an integer or not.**

text = input("Input a string: ")

if text.isdigit():
    print("The string is an integer.")

else:
    print("The string is not an integer.")

**_-Note: I was pleasantly surprised with how easy this one was! I had a little read up on canvas and saw this ".isdigit" function. With a little trial and error, I was able to write a nice, short code that gets the job done._**

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

### Activity 4
* **Write a Python program that ask user to input two numbers. Check if both numbers are divisible by 2 or 3, if yes multiply them and print them on screen. If not, add them and then print it on screen.**

num_1= int(input("Enter first number: "))
num_2= int(input("Enter second number "))
if num_1 % 2 ==0 or num_1 % 3 == 0 and num_2 % 2 == 0 or num_2 % 3 ==0:
    print(num_1 * num_2 )

**_-Note: Another short and sweet one! I find that creating a successful code, no matter how simple, is very satisfying and boosts my coding confidence._**

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

### Activity 5
* **Write a menu driven Python program that give user options to perform temperature conversion. Your code should be able to convert temperature from Celsius to Fahrenheit and vice versa.**

temp = input("Enter '1' to convert Celsius to Fahrenheit\nEnter '2' to convert Fahrenheit to Celsius\nEnter '3' to quit: ")
if "1" in temp:
    celsius = float(input("Enter the temperature in Celsius: "))
    fahrenheit = celsius*1.8+32
    print(str(celsius) + "° celsius is equivalent to " + str(fahrenheit) + "° fahrenheit")
elif "2" in temp:
    fahrenheit = float(input("Enter the temperature in Fahrenheit: "))
    celsius = ((fahrenheit - 32) *5 / 9)
    print(str(fahrenheit) + "° Fahrenheit is equivalent to", str(celsius) + "° Celsius")
    
**_-Note: Another satisfying code! I can be quite a meticulous person, so I really enjoyed combing out the finer (potentially unnecessary) details, for example: The comma in python creates a space, whereas the '+' does not! When adding in the '°' symbol, all the places where I have the '+' initially had a comma. I didn't want there to be a space between the integer and the '°' (e.g. 30° not 30 °). However, when I changed this, it gave me back an error!! It then took me a minute to realize that I needed to put the 'str' function in front of the integers as Python was trying to read it like an equation._**

**_-Note: Although I have added in the option "Enter '3' to quit", I am still unsure as to how to do this! I will be looking into it._**

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

**_-Note: I've found it so interesting to learn these codes! Even though they are simple, it's fascinating to learn the "behind the scenes" of, for example, a web page. Having used computers for the majority of my life, I've never really questioned how computing actually works. I may not be articualting myself in the clearest way, but when doing these exercises and some self-directed study, I constantly find myself thinking "Ohhh, that's how it's done!"._**


## 🌸💮🌸💮🌸💮🌸💮🌸💮 Week 4: Python tasks continued 🌸💮🌸💮🌸💮🌸💮🌸
                                   
### Activity 6
* **Write a Python program that takes distance and time as input and displays the speed in: meters per second, kilometers per hour, and miles per hour.**

meters = float(input("Input distance (meters): "))
hr = float(input("Input time (hours): "))
min = float(input("Input time (minutes): "))
sec = float(input("Input time (seconds): "))
hr_total = hr + (min / 60) + ((sec / 60) / 60)
sec_total = ((hr * 60) * 60) + (min * 60) + sec
kms = meters / 1000
miles = meters / 1609.344
print("Your speed in meters/sec is:", meters / sec_total)
print("Your speed in km/h is: ", kms / hr_total)
print("Your speed in miles/h is: ", miles / hr_total)

**_-Note: This one took me longer than it probably should have haha, I need to brush up on my maths skills. So many conversions! Very nice to see it working in action once completed though._**

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

### Activity 7
* **Write a Python program that takes 10 numbers as input from user and find their sum and average.**

Sum = 0
print("Please enter 10 numbers\n")
for i in range (1,11):
    num = int(input("Number %d = " %i))
    Sum = Sum + num

avg = Sum / 10

print("The sum of these numbers equals:", Sum)
print("The average of these numbers equals:", avg)

**_-Note: A slightly more difficult one for myself, combining different functions that I have just learned in some self-directed study. I like the use of %d and %i, a placeholder to specify integer values. Implementing loops is still new to me, I had to do a little bit of research and still have much learning to do! I'm also still not confident with lists, which I would like to use in this code, so I need to do some more practice._**

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

### Activity 8
* **Write a program in Python Sharp to display the multiplication table of a given integer.**

print("Multiplication Table (up to 10)")
num = int(input("Enter a number: "))
for y in range(1,11):
    print(num,"x", y, "=", num*y)
    
**_-Note: This one was a lot more simple, and I probably should be using it irl (I don't know all of my times tables). I'm also not sure what "Python Sharp" is! Is that how you get a table format?_**

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

### Graphs

This week in class there was a mention of graphs, but I couldn't see anything written about it on canvas. I know it was said that we don't have to know what graphs are, but hearing that other people had already written about it prompted me to do my own research. My initial knowledge of graphs was limited to pie charts and bar graphs, however I knew that this was unlikely to be what Roman was talking about. So after looking into what graphs are with a class mate, here is my new found understanding:
Graphs are a type of data structure (a way to store and organize data) that are commonly used in computer science. A graph is a collection of objects called nodes or vertices, that a connected with lines that are called edges. Graphs can be directed (sometimes known as a digraph), or undirected. A directed graph is named such because the connection, the edge, between each of the nodes goes only one way (Node "A" --> node "B"). This can be demonstarted with web pages: The web pages (with unique URL's) are the nodes. One web page(A) may have a link (the edge) to another web page(B), but it is likely that web page B will not contain a link to web page A. There are, of course, exceptions to this. The example of an undirected graph that was shown to me is a social network. For example: Facebook users are the nodes, and if two users are friends, this is the edge between them. This is an undirected edge because if User A is friends with User B, User B must also be friends with User A.

I observed online that my peers on campus were to make a video graph. (This is a side note, but my bad social anxiety is a reason I am drawn to IT. I will admit that I am thankful that I was not there, as being made to be the centre of attention in any way, peaks stress for someone like me. It is anxiety-inducing to be put on the spot and made to speak in front of the whole class, or forced to interact.) I spoke to one of my class mates who did physically attend this class, and I think I have an okay understanding. They were to video one person, while being videoed by another person, and so on, until somebody moves out of frame. In this circumstance, the people are the nodes, and the video is the directed edge between them. I think it is a directed graph because it needs to be more than 3 people participating (no two people are videoing each other). Video only goes one way.


## 🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮🌸 Week 5 🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮
                                            
### About Agile

Agile is a set of values and principles, or a collection of beliefs, that can be used as a foundation for making decisions about how to do the work of developing software. In the short Agile manifesto, it is stated that software can be developed better by valuing items on the left side over the items on the right side. These items are as follows:
* Individuals and interactions over processes and tools
* Working software over comprehensive documentation
* Customer collaboration over contract negotiation
* Responding to change above following a plan

It is the most commonly practised model in software development, as it "introduces the concept of fast delivery to customers using a prototyping approach". This prototyping approach is to divide the whole project into smaller chunks with specific features that can be developed quickly. The customer then gives feedback so that the prototype can be changed, or the development team can move on to the next prototype containing a new feature. 

**Three advantages of using the Agile model instead of the Waterfall model are:**
1. One benefit is the speed at which problems with the prototypes can be identified, and in turn how quickly and efficiently solutions can be created.
2. Another benefit (that I can relate to) is that the Agile model promotes productivity. As the developers are working in small increments, the work is more   manageable. The "finish line" of any prototype is always in sight. I believe I, and many others, would work better in these conditions.
3. As the Agile model is focused on customer collaberation, it only makes sense that the satisfaction of the customer is higher. They are able to constantly share their expectations, and continuously make changes as the development progresses.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

**What is an M.V.P.?**

M.V.P. stands for: Minimum Viable Product. Keeping within the spirit of Agile, M.V.P. is the first iteration of a product or solution that is useable. It contains 
enough features and is of a high enough quality that your customer can test it out and provide feedback, or you could be attracting your first set of customers. The 
main purpose of an M.V.P. is to gather feedback and information with the least amount of effort and money.


## 🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮🌸 Week 6 🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮🌸💮

### Prompts

#### Did you remember to take regular breaks away from your screen during this week? How often? Did you stretch your body?

I didn't think I would have a problem with forgetting to take breaks, however, it is easier than I expected to get caught up in studying or writing code, and not notice the time passing by. In an effort to implement healhy study habits, I now set a timer for 25 mintues of uninterrupted concentration, followed by 5 minutes of relaxing/doing something else.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is Timeboxing? Have you heard of it before? Will you use it?

I have not yet heard of Timeboxing, I'll be back after I research: I have learned that Timeboxing is a concept used in the Scrum framework, used to allot a certain amount of time to a particular task within a project. This ensures that the team will not spend too much or too little time/effort on said task.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### On a a 0-5 scale, how confident are you with each of the assignments?

I'd probably say my confidence for this assignment is a 4/5, only because I naturally have a lot of self-doubt, and I believe there is always room for improvement! My current confidence for the project assignment is probably also a 4/5, because I'm still not the best coder, but I'm very excited to create something!

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What are of you proud of up to this point in the course?

I'm most proud of how much Python I've learnt in my own time, as my past studying skills were never good. This time around I definitely applied myself more and took the time to learn. It is pretty daunting to learn coding, as when you first start, it's basically a foreign language and looks like nonsense. I'm by no means close to knowing everything about Python, but it doesn't seem like nonsense anymore.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is Python?

This is the very first definition I learned: Python is a high-level general-purpose programming language. High-level means that it is easier to read and more similar to english. I have learnt that Python is one of the most popular choices when it comes to coding, and is used in many different ways/places.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### Have you developed a habit of exploring?

I suppose it depends on the context. I have most definitely become more explorative in the world of coding, I've watched many hours of tutorials (not that I remember half of what they taught). The more I explore, the more I learn, the more intrigued I become, and so on! I'm excited to see where this takes me.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### Have you meditated before?

I have only tried to meditate, and failed. It is on my to-do list, as I know it is very beneficial for many people. I'm sure that if I implemented it into my daily life, it would likely reduce my anxiety! Or help me to think differently about my thoughts and behaviour. However, it is easier said than done, and requires much practice to become good at it.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### Is there something over which you have gained a degree of mastery before in your life? Gymnastics, Rubik's Cubes, A Video Game? What did it take?

I feel a little embarrassed to say that the only thing I would consider myself to have mastered are some video games! I think the word mastery holds a lot of power. To me, mastery means the best of the best, and by my own standards, I don't think I've mastered anything. But I've 100%'d many video games! I'm not _very_ embarrassed, because they do require some coordination, patience and memory! I also think that, with many things, video games are great in moderation, they make me happy and are a form of escapism.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### Do you consider yourself a developer yet?

Very simply put: no, I do not consider myself a developer yet (unless beginner/novice developer counts). Maybe after I finish my project assignment I will feel differently about this question.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### Do you value creativity? As a value itself? What about as a tool for learning to think logically?

I highly value creativity. I'm not sure if you've heard of the Myers Briggs personality test, but my personality type is known to be very creative and idealistic. Not to share too much information, but A.D.H.D. runs in my family, and it's a well known trait to be very creative! (It's also a very well-known trait to procrastinate and not get things done, even hobbies that we love, so that is actively fighting against my creative output). I'm not sure that I see creativity as a value in itself, but I do think it is a very important part of life, so maybe in that sense it could be a value. I am not sure that I know how to answer the last part of this question.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### How many tabs do you have open in your web browser right now? What is the ratio of study related tabs to distraction related tabs?

Today I have had about 7 different tabs open, but now only 3. I am _very_ prone to getting distracted (A.D.H.D. strikes again), so I keep my leasure/non-study-related tabs in a different window and minimize it. I'm not a huge fan of keeping tabs open, so there is only 1 tab open on that window. I don't think this is a bragging right or anything, because I would say that my phone is generally my biggest distraction.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is an IDE?

This is one of the very first programming terms I learnt (by the way, my self-directed python study has been on a wonderful app called Sololearn), and it means Integrated Development Enviroment. I don't have an expert definition, but as far as I know, they are places where you can write and run/test your code. My I.D.E. of choice has been PyCharm.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### So far, what was the hardest moment of this course for you?

I think the most challenging part of this course has been getting myself to put in the time! Admittedly, I get in my own way, and I always have whenever it regards learning. Procrastination is my middle name, I am working to fix this. For the most part, I really enjoy the challenges when I get around to doing them. An alternative answer to this question would be that I find some of the different teaching styles hard to go with, but I am new to study so I think it will become easier as time goes on.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is OOP?

O.O.P stands for object-oriented programming. I have heard of this term quite a few times, but I have never been able to fully understand what it means. I think when I see more examples it will become more clear to me.

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### Are you using the canvas content? Do you find it helpful or tedious?

In a perfect world I would have read all of the content on canvas, but alas, this is not so. I do wish I was that person though! I have referred to it many times for specific topics though, and I do find it helpful! It has a lot of good information. 

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is polymorphism?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### Did you hear a self critical voice in your head throughout the process of learning during this last few weeks? What did it say to you? Do you believe what it said?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is an MVP? How would you describe it to a group of 6 year olds?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is the hardest problem you have solved so far?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is pair programming?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What are you looking forward to learning about programming?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is conscious listening?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is a variable?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What programming languages are you interested in learning? Why?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is something kind that someone has done for you?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### If you were describing programming to someone who knows nothing about it, what would you say?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### Which parts of this course made you feel doubtful of your own innate ability?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is a fixed mindset?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### What is something kind you have done for someone else?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### Have you done mindfulness or attention training before?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿

#### Have you developed a habit of persevering?

✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿•❀•✿
