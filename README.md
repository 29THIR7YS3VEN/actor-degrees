# AI command-line program in python that uses breadth-first search to find how many 'degrees of separation' two actors are. Made for cs50AI
According to the game 'Six Degrees of Kevin Bacon,' any actor can be connected to any other actor in Hollywood through linking which movies they starred in. This AI algorithm uses breadth-first search to find shortest path between any two actors by choosing a sequence of movies that connects them.
## Example
```
Name: Emma Watson
Name: Jennifer Lawrence
3 degrees of separation.
1: Emma Watson and Brendan Gleeson starred in Harry Potter and the Order of the Phoenix
2: Brendan Gleeson and Michael Fassbender starred in Trespass Against Us
3: Michael Fassbender and Jennifer Lawrence starred in X-Men: First Class
```
## Usage
- Install dependencies
`pip install -r requirements.txt`
- Run program 
`python degrees.py [directory]` 
Where [directory] is the name of the directory containing the CSV files movies, people, stars.
- The program will then prompt the user for the name of two actors before computing the degrees of separation.

## Credits
- Code written predominantly by CS50AI
- `shortest-path` function written by emman29
- Database used curtesy of IMDb, used with permission.
