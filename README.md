# importing package
from better_profanity import profanity

# text censored
text = "What the shit are you doing?"

# censoring
censored = profanity.censor(text, '$')

# view output
print(censored)
