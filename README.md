import random

responses = [
    "it could be",
    "i don't think so",
    "YES!!!",
    "HELL NO",
    "possibly",
    "it won't work",
    "you probably won't",
    "it depends",
    "probably",
    "the world shall decide",
    "its giving no",
    "it giving hell yes",
    "the path has already been shown",
    "much likely",
    "unlikely",
    "just stop",
    "it won't be",
    "Nope",
    "Nah",
    "Not a chance",
    "No way",
    "Absolutely not",
    "I don't think so",
    "Negative",
    "Nuh uh",
    "Denied",
    "Try again later",
    "Absolutely",
    "Yeah, for sure",
    "Yup",
    "Totally",
    "Mhm",
    "Of course",
    "Yes sir",
    "You got it",
    "For real",
    "Confirmed",


]

print("ask the magic 8 ball anything (type \"stop\" if you don't want to do this anymore) ")

while True:
    user_input = input("your question? > ").strip().lower()

    if user_input == "stop":
        break
    else:
        print(random.choice(responses))
