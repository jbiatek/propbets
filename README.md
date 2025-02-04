# Prop Bets

This is a game that I made for Super Bowl prop bets. I run it with a private live server, but for the general public, I've made this version which is totally static, using your browser storage to save changes.

## The game

Every year, all the betting sites offer a bunch of silly or specific wagers about The Big Game, both the actual football and all the stuff around it. Think "what color will the Gatorade shower be" or "will a kick hit the uprights." I love the idea but don't want to actually gamble, so I hand-select the best ones and turn them into a fun and free game for my friends.

Each question is based on a real $100 bet, and the scores are calculated accordingly. The higher risk answers are also higher reward, but players lose 100 points for each wrong answer.

## Running the game

The page can be found here: https://jbiatek.github.io/propbets/

Fill out the forms as directed, and data will be stored in your browser's local storage. If you need TiddlyWiki's full controls, there is a checkbox on the home page for turning off "simple" mode.

For in-person play, it should be sufficient to have everyone fill in their entry on whatever computer is going to display the results for everyone. You can also have people fill out the form and send you their JSON, which can be found at the end of the entry form. Create a corresponding entry on your end, edit the entry, and paste their JSON to fill in the answers.

The Dashboard will have a leaderboard of all the entries, and you can grade them with the answer editor linked to on the home page.

If you really really want to go all out, run a Node.js TiddlyWiki server and pull the two plugins out of this page and into your wiki. The "Offline Mode" and "Entry Form" pages are your starting point, and should probably be set as your default tiddlers.
