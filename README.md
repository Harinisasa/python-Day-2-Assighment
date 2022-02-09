# python-Day-2-Assighment
lottery = "hello coders"
# 'h' or 'e' or 'o' or 'c' or 'd'

print("Choose correct character of the word '",lottery,"' to win the lottery")

inputs = input(" ").lower()

if inputs == lottery[0] or inputs == lottery[1] or inputs == lottery[4] or inputs == lottery[6] or inputs == lottery[8]:
    print("congratulation, you won the lottery prize")
else:
    print ("Sorry, Better luck next Time")
