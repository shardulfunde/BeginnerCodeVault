# College Ranker

## Description
The **College Ranker** script helps users evaluate and rank colleges based on user-provided ratings for three key aspects:
1. **Campus** (scored out of 5)
2. **Placements** (scored out of 10)
3. **Crowd** (scored out of 5)

By aggregating these ratings, the script generates a total score for each college and ranks them accordingly.

---

## Features
- **Interactive Input**: Users can input college names and assign ratings interactively.
- **Customizable Ratings**: Allows users to score each college based on personal preferences.
- **Automatic Ranking**: Colleges are ranked automatically based on their total scores.
- **Easy to Use**: A simple and user-friendly command-line interface.

---

## How to Use
1. Run the script in a Python environment.
2. Type the name of each college when prompted. Type `00` to stop adding colleges.
3. Provide ratings for each college's campus, placements, and crowd when prompted.
4. The script will display a ranked list of colleges based on their total scores.

---

## Example Usage
```plaintext
Type the college name or press 00 to confirm: College A
Your current college list is ['College A']
Type the college name or press 00 to confirm: College B
Your current college list is ['College A', 'College B']
Type the college name or press 00 to confirm: 00

Rate campus of College A (out of 10): 8
Rate placements of College A (out of 10): 9
Rate crowd of College A (out of 10): 7
Rate campus of College B (out of 10): 6
Rate placements of College B (out of 10): 8
Rate crowd of College B (out of 10): 9

Rank 1, Points- 21.0, college- College A
Rank 2, Points- 20.5, college- College B
