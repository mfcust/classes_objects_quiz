# classes_objects_quiz

Here we are going to use the concepts of classes and objects to create a multiple choice quiz! Let's say you wanted to create a question class. The charactersitics of a question would be the prompt and the answer! So, we can create the following class:
```
class question:
  def __init__(self, prompt, answer):
    self.prompt = prompt
    self.answer = answer
```

Let's say I wanted to create a one question quiz. First, I would create a question object with a prompt and an answer:
```
prompt1 = question("Should you look directly at the sun? \n(a) Yes\n(b) No\n\n", 'b')
```
Then, I could ask the question using an input function:
```
answer =  input(prompt1.prompt)
```
Then, I could check to see if the answer I put is correct!
```
if answer == prompt1.answer:
  print("You are correct!!")
else:
  print("You are incorrect :(")
```
Navigate to the python file and try running this code in your text editor. Once you understand how it is working, answer the question in the python file.
