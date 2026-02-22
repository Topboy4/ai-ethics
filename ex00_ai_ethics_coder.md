Exercise 00: Learning to Use AI Ethically as a Coder
Part A: The Critical Distinction
Write down your honest answers:
QUESTION: How have you used AI for coding so far?
ANSWER: I've used AI for coding so far by using it to understand complex logics, debug, and sometimes write function that i'm not familiar with, for example i was struggling to understand a function i got because i wasn't familiar with the syntax


QUESTION: Do you ask AI for solutions before trying yourself?
ANSWER: Not really, i sometimes ask for the logic behind problem im not familiar with


QUESTION: Can you explain code you've submitted without AI's help?
ANSWERYes i can, sometimes even codes that are not written by me, if i take out some minutes to study it, i can explain it, especially if it's not so complex.


QUESTION: What would happen if AI was suddenly unavailable during an exam or interview?
ANSWER:I might feel a little bit of reflex panic at first, but then i'm sure that i will still be able to solve problems.
Identify your current pattern: Which learner are you now?
* Learner B: "AI is my learning amplifier"


Attempts the problem first
Asks: "Why does this approach work? What are the trade-offs?"
Tests understanding by explaining concepts
Uses AI to explore deeper, not to avoid thinking
Write a brief paragraph: Where are you now, and where do you want to be?
Today, i'm sincerely currently in a position where i use AI to learn but could sometimes be caught in a situation where i tend to rely on AI because of the result and how easy it could make things be, although i will always come back to ask questions ('WHY' and 'HOW') so i just don't follow blindly, the effect has been doubled-edge, I want to become a learner that uses AI the right way only, which is, using it to amplify my learning because i don’t want to entirely rely on AI for answer, because AI is a tool that i'm suppose to think to and not make it think for me. Henceforth, i need to employ a couple of strategies like the 15 Minutes Rule.
Part B: The Wrong Way vs. The Right Way
Track B — The Right Way

START
INPUT text
CONVERT text to lowercase
REMOVE all spaces from text
REVERSE the cleaned text
IF reversed text equals cleaned text PRINT "It is a palindrome" And Returns True ELSE PRINT "It is not a palindrome" And Returns False
END


Implement your solution in Python.


def is_palindrome(text):
   text = text.lower()
    text = text.replace(" ", "")
    reversed_text = text[::-1]
    if text == reversed_text:
       return True
    else:
       return False



Code tester
print(is_palindrome("racecar")) # prints True 


print(is_palindrome("hello")) # prints False(because its not a palindrome) 


print(is_palindrome("A man a plan a canal Panama")) # prints False


Step 2: Strategic AI use After you have a working solution, ask AI:
Part C: Testing Your Understanding
QUESTION: What's the time complexity?
ANSWER: The overall time complexity is O(n).
QUESTION: What edge cases am I missing?
ANSWER: They're empty string, string with only spaces, string with only symbols or punctuation, single character, mixed whitespace (tabs/newlines), Unicode or accented characters, and cases where non-alphanumeric characters should be ignored.
QUESTION: Alternatives and trade-offs?
ANSWER: Reverse-and-compare (text == text[::-1]) is simplest but uses extra memory, build a cleaned alphanumeric string then compare (more correct for sentences but still O(n) space), two-pointer in-place comparison (most memory-efficient, O(1) extra space, slightly more complex), and regex cleaning (flexible but slower).
QUESTION: How does it perform on very long strings?
ANSWER: For very large input (e.g., millions of characters), your version remains O(n) time but uses O(n) extra memory because it creates multiple full copies of the string, which can cause high memory usage and allocation overhead. A two-pointer approach avoids copying and is more efficient for extremely large strings.

Step 3: Reflection
QUESTION: What did you learn by struggling first?
ANSWER: i learn on depending on my own idea or logic and exploring many ways to come about building the code the function correctly.I learnt that it's possible to thing about the logic behind every code oe function,and with the help of pseudocode that seems like using regular human interpretation or language to interpret the logic, also learnt that you will get the best from AI if you can first of all attempt the problem yourself.
QUESTION: How is your understanding different than if you'd just asked for the solution?
ANSWER: my understanding is different now because I'm not skipping the learning phase and  that AI is an assistant and not the boss, the result from AI should be my idea, I am the thinker

QUESTION: Can you now implement similar functions (reverse a string, find duplicates) without AI?
ANSWER: yes i can make attempt on it
QUESTION: What mental model did you build?
ANSWER:I build a mental model so I can trust and feel confident in everything I write  from each line of code to the entire program  and I only use AI tools after making multiple attempts at a task, using them to deepen and accelerate my understanding.


Part C: Testing Your Understanding
modified code to:
              *   Ignore spaces and punctuation

              *  Make it case-insensitive

              *  Return the position where the string stops being a palindrome (if not a
                 palindrome)


Modified CODE
def is_palindrome(text): # makes case insensitive text = text.casefold() string = ""
for char in text:
    # accepting only alphabet and numerics
    if char.isalnum():
        string += char
# two pointer indexing
left = 0
right = len(string) -1
# looping
while left < right:
    # palindrome validation
    if string[left] != string[right]:
        return False, left, right

    left += 1
    right -= 1
return True, None, None

Part D: The Fairness Contract
I will use AI when:
After I've attempted a problem for at least 20 minutes

To understand why my solution works/doesn't

To explore alternatives after I have a working solution

i want to make research on some learning resource for learning amplifying

I will NOT use AI when:
I haven't tried the problem myself

I'm taking an assessment or test

I need to build fundamentals

handling sensitive and confidential information

Signed :Sunday Aboh
DATE : 16 Feb 2026

Part E: Real-World Scenario Analysis
Interview: "Explain how you'd implement a caching system." If you always relied on AI, can you answer?
ANSWER: if i have always relied on AI, I will have to brain storm to see if i can come up with something, it might not be correct but i will attempt it by using logic behind caching system as a way of saving frequently used data.

Production bug at 2 AM: AI is unavailable. Can you debug code you don't fully understand?
ANSWER: The chance of me being able to debug it is very slim and almost impossible, if i understand the logic behind it i will attempt it still. Make some research base on the lines of code that seems new to me then ill get a clue on it to be able to fish out the bug and get the code to run well.
New tech with little documentation: If you never learned to read docs and experiment, what happens?
ANSWER: I will learn outside AI, by checking other resources to learn, read documentation about the library and practice.
Write a paragraph: How does using AI fairly now prepare you for these scenarios?
 I know I'm using AI fairly when:
Using AI fairly today, prepares me for real-world challenges because i consider it to be a learning tool, that would help with prescision when learning, help me build integrity, When I use AI as a support tool or learning amplifier rather than a shortcut or answer generator, I learn how to verify information, understand concepts and logic deeply.

Part F: Building Irreplaceable Skills
Problem Decomposition
Breaking down problems logically rate: 3/5 IP: outline logically before attempting coding and use of pseudocode
Systems Thinking
Understanding how components interact rate: 2/5 IP: i will research to properly understand the different stages and road map and study architecture design.
Critical Evaluation
Knowing when code is wrong or inefficient rate: 2/5 IP: Compare my code with other solutions and resources and search for edge cases
Debugging Mindset
Investigating unexpected behavior rate: 3/5 IP: I will separate failed section so i can get proper understanding
Conceptual Understanding
Knowing WHY, not just HOW rate: 3/5 IP: i will attempt to explain the concept without code first then read and research more
Lowest is System Thinking 3 specific actions I'll take this week to improve it without relying on AI.
1.Read documentation related to the project and know how best to go about it 
2.learn and understand how system interact
3.learn the Use diagram to interpret flows
