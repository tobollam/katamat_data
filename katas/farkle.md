# Farkle Kata

## Task

Write a scoring method that calculates the best score based on a single roll with five dice using the following set of scoring rules. 

### Rules 

- A single one (100 points)
- A single five (50 points)
- Triple ones [1,1,1] (1000 points)
- Triple twos [2,2,2] (200 points)
- Triple threes [3,3,3] (300 points)
- Triple fours [4,4,4] (400 points)
- Triple fives [5,5,5] (500 points)
- Triple sixes [6,6,6] (600 points)

### Example Scores

- [1,1,1,5,1] = 1150 points
- [2,3,4,6,2] = 0 points
- [3,4,5,3,3] = 350 points

### Extra Tasks

Modify your scoring method to support the following rules:

- The player may throw 1 to 6 dice at a time.
- Four-of-a-Kind [2,2,2,2]: Multiply Triple score by 2 (e.g. 4 2s = 400)
- Five-of-a-Kind [2,2,2,2,2]: Multiply Triple score by 4 (e.g. 5 2s = 800)
- Six-of-a-kind [2,2,2,2,2,2]: Multiply Triple score by 8 (e.g. 5 2s = 1600)
- Three Pairs [2,2,3,3,4,4] (800 points)
- Straight [1,2,3,4,5,6] (1200 points)

## Resources

- https://en.wikipedia.org/wiki/Farkle