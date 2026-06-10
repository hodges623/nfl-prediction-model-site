Updating the site each week
1. Generate (This is done in python automatically):
	a. data/nfl_predict_outcomeYYYYwX.csv

2. Add entries to html/manifest.json (Done automatically in python):
	a. ex: { "season": 2026, "week": 2, "file": "nfl_predict_outcome2026w2.csv" }

3. Commit and push with Git Bash (Done automatically in python):
	a. cd "G:\My Drive\nfl-model-site"
	b. git add .
	c. git commit -m "Add week X predictions"
	d. git push
