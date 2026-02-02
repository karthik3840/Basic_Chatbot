while True:
    user_input = input().lower()

    if user_input == "hello":
        print("Hi!")
    elif user_input == "how are you":
        print("I'm fine, thanks!")
    elif user_input == "bye":
        print("Goodbye!")
        break
    else:
        print("Sorry, I don't understand.")
