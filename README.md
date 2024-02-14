# fh# Creating a collection of signals using a list
signals = [0.5, 0.8, 0.3, 0.9, 0.2]

# Accessing individual signals
print("First signal:", signals[0])
print("Second signal:", signals[1])

# Adding a new signal to the collection
signals.append(0.7)
print("Updated signals:", signals)

# Iterating over all signals in the collection
print("All signals:")
for signal in signals:
    print(signal)
