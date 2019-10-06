# FLL Tournament Scorer by EV3Lessons

This is a version of the FLLTutorials/EV3Lessons INTO Orbit Scorer that is designed for tournaments. It has team management along with a score board.

It uses Google Sheets/Drive APIs to manage scores and organize referees.

This is version EV3Lessons Tournament scoring system v4.3.0 and runs off EV3Lessons Scorer v3.3.1.

If you are looking for a version that does not need internet connection (but only a local network), look at https://github.com/sanjayseshan/tournament-scorer-offline, which uses a local server.

To run, use a Python HTTP server:
<code>python -m SimpleHTTPServer 8000</code> --> run in this directory,

If you use our key, it can only be accessed from our site or http://localhost:8000/

The tournament API for any tournament is easy:<br><br>
<b> URI Parameters: </b>
* ?tourn=<TOURNAMENT_NAME>
* ?save=<GOOGLE_SHEET_TO_SAVE_SCORES>
* ?mission=<GOOGLE_SHEET_TO_SAVE_MISSIONS_COMPLETED>
* ?lang=<2_LETTER_LANGUAGE_CODE>
* ?team=<TEAM_NUMBER> (Scorer)
* ?round=<ROUND_NUMBER> (Scorer)
* ?index=<TEAM_INDEX_TO_SAVE_TO> (Scorer)
