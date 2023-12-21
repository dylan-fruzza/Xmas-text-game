 #!/bin/python3
import time as t
yes_no = ["yes", "no"]
x = ["1","2"]
options2 = ["Find a sleigh to ride in", "Find another way home" ]
options1 = ["Go talk to Santa", "Find another way home"]
options3 = ["Disguise yourself as an elf", "Find another way home"]
health = 100

def check_answer(answer_list, answer):
  while answer not in answer_list:
    answer = input("\nPlease enter answer again:")
    t.sleep(1)

def choose(options):
  tracker = 0
  for choices in options:
    print(x[tracker], ". " , choices)
    tracker = tracker + 1
    t.sleep(0.5)
    
t.sleep(1)
    
print("""Welcome to Xmas Escape! You need to escape the 
North Pole before Santa finds you or your health reaches zero.\n""")

t.sleep(2)

print("""You were so excited on Christmas day that you 
waited on your roof for Santa. Once he came, 
you sneaked into his slay to see your friends 
toys. As you were looking you felt the slay 
move. You looked outside to see the slay 
moving! In a few minutes, you arrived at the 
North Pole. What are you going to do?
""")
t.sleep(5)

choose(options1)
answer1 = input("\nWrite the number behind the answer you chose:")
check_answer(x, answer1)

if answer1 == "1":
  print("""\nYou hear the elves talking about a stowaway. 
They said that if the stowaway is caught, they
will be on the naughty list for 7 years. This
breaks your heart to hear this. Health minus
10.
""")
  t.sleep(1)
  health -= 10
  print("Health:",health)
  t.sleep(2)
  print("""\nOn your way to figure out how to get home, you 
hear that the elves are going to check all of 
the presents that Santa delivered. They're are 
going to see if he delivered were all the 
right presents. What to do?\n""")

  choose(options2)
  answer2 = input("\nWrite the number behind the answer you chose:")
  check_answer(x, answer2)

else:
  print("""\nOn your way to figure out how to get home, you 
hear that the elves are going to check all of 
the presents that Santa delivered. They're are 
going to see if he delivered were all the 
right presents. What to do?\n""")

  choose(options2)
  answer2 = input("\nWrite the number behind the answer you chose:")
  check_answer(x, answer2)

if answer2 == "1":
  print("""\nAs you try to find where the sleighs are, you 
stumble across a map that helps you find out
where all of the rooms are and what the rooms 
used for. The problem is that an elf is 
already using the map and doesn't look like 
he is leaving any time soon. What to do?\n
""")
  
  choose(options3)
  answer3 = input("\nWrite the number behind the answer you chose:")
  check_answer(x, answer3)
  
  
else:
  print("""\nAs you look around for an escape route, you
see Santa. In seconds, the elves find you 
and bring you home you are put on the 
naughty list forever. :'(\n
  """)
  t.sleep(2)
  print("GAME OVER")
  
if answer3 == "1":
  print("""You find an elf costume in a closet and you 
check out the map. The elf speaks in a 
language you have never heard of 
before. The elf realizes this and
talks into something you've never seen
before. other elves come in and take 
you home you are put on the naughty 
list forever. :'(""")
  t.sleep(2)
  print("\nGAME OVER")
  
else:
  print("""The elf leaves after a while of waiting, so 
you look at the map and find the sleigh 
room. You then stowaway on the sleigh
until you reach you house :)""")
