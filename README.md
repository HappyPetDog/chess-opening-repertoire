# **Popular Chess Openings based on Rating and Time Control**
## **Abstract:** 
This Python Notebook aims to gather the most popular chess opening repertoire depending on the player's rating and chosen time control, which will help the player know what opening is played the most at their specific level and time format. By analyzing a large dataset of chess games from various online platforms, this project will identify patterns and trends in opening choices among players of different skill levels (e.g., beginner, intermediate, advanced) and across different time controls (e.g., classical, rapid, blitz, bullet). The insights derived from this analysis can provide players with a strategic advantage by informing them of commonly encountered openings in their games, enabling them to add these to their arsenal and improve their overall performance.

## **Dataset:** 
The games found in the PGN file is extracted from the database of FICS (Free Internet Chess Server). The link to the website can be found [here](https://www.ficsgames.org/download.html). The games extracted were from the entire year of 2023, and it included every time control and every player rating.  

## **Summary of Findings:**
Upon examining the top 10 most used openings based on every category, here's the summary of what chess openings to look out for:

### **At the `beginner` level:**
* When playing `blitz`, `white` has a win rate of `50.90%` when playing `A00` or the `Polish (Sokolsky) opening`. `black` has a win rate of `50.95%` when playing `B00` or the `King's pawn opening`. Despite not being played much, `A04` or the `Reti Opening` has a win rate of `74.26%` when `white` plays it, so `black` needs to watch out for this opening. 
* When playing `rapid`, `white` has a win rate of `53.78%` when playing `D00` or the `Queen's pawn game`. It also has a win percentage of `64.92%` when the King's pawn opening is played. Unfortunately for black, there's only one opening in the top 10 that has over 50% win rate. That opening is `A00` or the `Polish (Sokolsky) opening`, which has a win rate of `55.56%`. 
* There are only less than 20 `bullet` and `classical` games played at this level. Hence, it's challenging to make further conclusions based on the resulting data. 

### **At the `intermediate` level:**
* When playing `blitz`, `B20` or the `Sicilian defence` has the highest win rate of the top 10 against `white` with `54.49%`, while `D02` or the `Queen's pawn game` has a win rate of `55.91%`, which is also the highest among the top 10 when played against `black`. 
* When playing `rapid`, `B30` or the `Sicilian defence` has the highest win rate for `black` with `58.30%`, while `B00` or the King's pawn opening wins `64.92%` of the games for white. 
* When playing `bullet`, `B01` or the Scandinavian (centre counter) defence has the highest win rate of `63.45%` for `black`. For `white`, `D00` or the `Queen's pawn game` allows them to win `66.05%` of the games played. 
* When playing `classical`, despite being in the lower top 10 in terms of usage, `C00` or the `French defence` wins `57.89%` of the games for `black`, while `C44` or the `King's pawn game` wins 54.69% of the games for `white`.

### **At the `advanced` level:**
* When playing `blitz`, a majority of the openings leads to a draw in `15%` of the games, leading to a win rate of below 50% for both black and white. Nonetheless, `B30` or the `Sicilian defence` has the highest win rate for `black` with `61.017%`, whereas `C50` or the `Italian Game` won `57.30%` of the games for `white`. 
* When playing `rapid`, despite only having 49 - 132 games played, `D45` or the `Queen's Gambit Declined semi-Slav with 5.e3` wins `56.72%` of the games for `black`, whereas `A45` or the `Queen's pawn game` won `51.40%` of the games for `white`. 
* When playing `bullet`, only one one opening has seen play in nearly 200 games, while the rest are below 50. That is `A00` or the `Polish (Sokolsky) opening`, which wins `50.78%` of the games for `black`. 
* There are only less than 30 games played for `classical` at this level. 