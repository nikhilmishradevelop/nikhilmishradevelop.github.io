Final Solution Notebook
-----------------------
final_notebook.ipynb

Final Solution Submission File
------------------------------
final_submission.csv

Approach
---------

I used a weighted blend of Roberta-base and Roberta large, in total 4 models, by varying the number of epochs, and tuning some parameters.

Libaries Used
--------------

-> simpletransformers

Notes
-----

1. Due to seeding issues, my current solution generates a score a bit worse than my best submission. The current submission scores 0.496836, on the leaderboard.

2. Deep Learning solutions have a problem of seeding, and the solutions may not be exactly reproducible, however my solution will produces the best submission on the leaderboard, everytime I run it.

P.S: Lastly thank you ZINDI, for organizing such a wonderful hackathon, looking forward for more such hackathons.