Code used to gather and generate the data for the HN 2019 Who Is Hiring infographic.

### Data:
* Raw counts of every word - `word_counts.pkl`. This is a Counter object that contains the raw word counts of every post from each month. So, for example, if the post said: "Google wants python devs", the object reads: ("Google":1, "wants":1...).
* Skill counts - `skill_data.csv`

![Who's Hiring](infographic.png)

To run: 

`jupyter notebook` and run each cell sequentially.

