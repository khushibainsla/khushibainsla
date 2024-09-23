# Function to calculate probability
def calculate_probability(successful_outcomes, total_outcomes):
    return successful_outcomes / total_outcomes

# Example: Probability of getting heads in a coin flip
successful_outcomes = 1  # Only 1 head in a coin
total_outcomes = 2  # Two possible outcomes: heads or tails

probability = calculate_probability(successful_outcomes, total_outcomes)
print(f"The probability of getting heads is: {probability}")

