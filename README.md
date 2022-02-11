# Prop Bets

This is a game that I made for Super Bowl prop bets. I run it with a private live server, but for the general public, I've made this version which is totally static, using your browser storage to save changes.

## The game

Every year, all the betting sites offer a bunch of silly or specific wagers about The Big Game, both the actual football and all the stuff around it. Think "what color will the Gatorade shower be" or "will a kick hit the uprights." I love the idea but don't want to actually gamble, so I hand-select the best ones and turn them into a fun and free game for my friends.

Each question is based on a real $100 bet, and the scores are calculated accordingly. The higher risk answers are also higher reward, but players lose 100 points for each wrong answer.

## Running the game

The page can be found here: https://jbiatek.github.io/propbets/

The simplest thing to do is have everyone fill out the form for themselves, then compare answers and scores afterward. I will update the page with the answers after the game, and then it *should* update after refreshing the page, and scores will be visible on the dashboard. 

If you want to get fancier, have people fill out the form themselves and ask them to send you their answers. Once the form is finished, they'll see the code for their answers at the end (this is really a very simple JSON file). If you collect all those answers, you can copy-paste the JSON into each entry (use the edit button in the top right to paste the JSON), then you'll have everyone's entries in one place. Once the answers are in, the Dashboard will have a leaderboard of all the entries. You can also fill the answers in on your own, there's a link to the Answers key on the wiki. If you fill out the answers yourself live, the Dashboard will update live too. Note that if you fill out the answers, it'll override my update with answers unless you delete the Answers entry entirely and then reload.

If you really really want to go all out, run a Node.js TiddlyWiki server and import the tidddlers from this file to create a live clone. You'll probably want to disable or delete the Browser Storage plugin, since that can only cause confusion with an actual server. 
