# Dog Ratings - Advanced Wrangling
Created: October 20, 2018<br>
Latest Update: October 23, 2018<br>
By: Can Bekleyici - bekleydata.com<br>

<img src="project4.jpg" height="400px" width="500px">

## Summary
This project aims to to get insightful information about dog ratings from the twitter page WeRateDogs™, while demonstrating advanced data wrangling and visualization techniques using various Python libraries. WeRateDogs™ is a community page on twitter designated to rating dogs on their appearences and stories, and which was formed by the user @dog_rates in 2015. The page has since grown extremely in popularity, with many users sharing its content and requesting their dogs being rated aswell. The site is a driving force for the development of the 'dog culture', with it's famous terms like "pupper", "mlem", "floof" etc. They also developed their own unusual rating system over time, in which almost every dog is rated above 10/10, because "they're good dogs".

To achieve the goals of the analysis, data have been gathered from different sources, including the twitter api as well as other web data. The potentials of Python's pandas library has been used extensively on the assessment and data cleaning parts. For the conclusion part, statements regarding the performance of each dog breed and dog stage (age group) have been given. To sum up the conclusions, visualizations in forms of word clouds have been plotted in accordance to the observations.

## Prerequisite
### Files that are included:
<ul><li><code>wrangle_act.ipynb</code> - The main code for this project as a jupyter notebook</li>
  <li><code>wrangle_report.ipynb</code> - A description of the data wrangling process in this project</li>
  <li><code>act_report.ipynb</code> - A blog post and report of the key findings of this project</li>
  <li><code>environment.yaml</code> - The environment file for this project</li>
  <li><code>requirements.txt</code> - All packages and their versions listed in a txt-file</li>
  <li><code>twitter-archive-enhanced.csv</code> - Dataset with original tweet data from the @dog_rates twitter channel</li>
  <li><code>image-predictions.tsv</code> - Dataset with pre-made predictions about the dog’s breeds</li>
  <li><code>tweet_json.txt</code> - JSON file containing metrics from the twitter api</li>
  <li><code>twitter_archive_master.csv</code> - dataset containing the master data frame after cleaning</li></ul>

### Installation:
In order to run the project on your local <code>Anaconda</code>, download all the files and run `wrangle_act.ipynb` on your jupyter notebook. Note that in order to run all the cells, you will have to fill to respective parts with your own twitter api keys.

### Without Installation:
You can view the complete code by using the GitHub built-in Notebook Viewer with `wrangle_act.ipynb` without any prerequisitions.
