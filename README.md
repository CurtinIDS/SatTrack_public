# SatTrack

SatTrack is a mobile and web app that allows users to photograph the night sky and find satellites.
The website is hosted at [https://d6gshunmt1czl.cloudfront.net/](https://d6gshunmt1czl.cloudfront.net/).

This is the public facing component of the SatTrack repository.

## Instructions

### Updating the weekly challenge objects

Edit the file `weeklyChallengeData.csv`, to include your object of interest (use NORADID) and to provide a short encouragement message that will be displayed on the website.
The file format is `.csv` with the following columns:
- `week_no`. Week of year, as an integer
- `norad_cat_ids`. At least one, but possibly multiple NORADID for the objects to be tracked. This is a string, separated by commas if there are multiple entries.
- `notes`. Text. This will be displayed on the leaderboard page of the website, and acts as messages to encourage people to observe. It is recommended that you put the common name of the object(s) here so that people can identify them on [heavens-above.com](https://www.heavens-above.com/).

### Feedback on the web app

- Please submit a github issue to this repo, using the template provided.
