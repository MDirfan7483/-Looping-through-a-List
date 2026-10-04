# -Looping-through-a-List-string-numbers-of-time
step one of learning

scores = [85, 90, 78, 92]
total = 0
for score in scores:
    total = total + score
print(f"The total score is {total}")


word = "Python"
for letter in word:
    print(letter.upper())
for number in range(5):
    print(f"Downloading file {number}...")

    auther-irfan
    
The Gold Miner

 mine = ['rock', 'gold', 'dirt', 'gold', 'gold', 'rock', 'dirt']
gold_count = 0
for item in mine:
    if item == "gold":
        gold_count += 1  # Shorthand for: gold_count = gold_count + 1
print(f"You found {gold_count} pieces of gold!")
