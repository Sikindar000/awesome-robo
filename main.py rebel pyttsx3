import pyttsx3

engine = pyttsx3.init()
print("Welcome to robo speaker created by sikinder version 1.1")
while True:
    user_input = input("Enter the text you want the robot to speak: ")

    if user_input.lower() == 's':
        # Stop the program if the user types 's'
        break

    # Set the speech rate and volume
    engine.setProperty('rate', 150)
    engine.setProperty('volume', 1.0)

    # Use the default voice to speak the text
    engine.say(user_input)
    engine.runAndWait()