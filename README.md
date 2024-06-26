# What Could Go Wrong - Peer Production and Communities Edition

## For current dauphine students - add your prompts and responses to the respective csv files. These can be converted to pcio later.

This repository hosts the files used for the What Could Go Wrong? digital card game. Nikolas Martelaro and Wendy Ju developed and presented the game at a Workshop at AutoUI 2020. The game was then modified by Nik and his team at CMU to be more generalized for AI-based systems.

The version here presents a further iteration on the game. In this iteration, prompts focus on peer communities, online and in person. Example applications are drawn from two sources: Kaddour et al.(2023) and FlowGPT.com. The list of potential ethical issues stems from wide range of sources, including the online peer collaboration of Dauphine Students. Existing prompts for AI and other iterations have been narrowed down, and added to by students. Besides, this iteration of the game includes a LaTeX template, which can be used to convert the digital card game into a physical card game.

The digital card game can be loaded into and played on PlayingCards.io. Custom cards can be added using the `csv` files for `prompts` and `responses`
111
### References

Baker, S.D. and Comer, D.R. (2012) '"Business Ethics Everywhere": An Experiential Exercise to Develop Students' Ability to Identify and Respond to Ethical Issues in Business', Journal of Management Education, 36(1), pp. 95--125. Available at: <https://doi.org/10.1177/1052562911408071>.

Floridi, L. et al. (2021) 'An Ethical Framework for a Good AI Society: Opportunities, Risks, Principles, and Recommendations', in L. Floridi (ed.) Ethics, Governance, and Policies in Artificial Intelligence. Cham: Springer International Publishing (Philosophical Studies Series), pp. 19--39. Available at: <https://doi.org/10.1007/978-3-030-81907-1_3>.

Kaddour, J. et al. (2023) 'Challenges and Applications of Large Language Models'. arXiv. Available at: <https://doi.org/10.48550/arXiv.2307.10169>.

## Abstract

While peer communities have the potential to support and improve our daily lives, there are also challenges and potential downsides to these practices. In this workshop, we intend to foster discussions about the potential negative aspects of online and peer communities in hopes of surfacing challenges that should be considered during the design process rather than after deployment. We will spur these conversations through a review of participant position statements and through group discussion facilitated by a card game called "What Could Go Wrong?" Our goal is to consider the collective creation model, improving technology, and reducing potential drawbacks. By identifying potential harms and downsides, the game players, and the community more broadly can design well-considered solutions.

## Game Setup Instructions

1.  Download this repository
2.  Go to <https://playingcards.io/game/standard-deck> to start a custom deck
3.  Enter the virtual card table
4.  Click the `Edit Table` icon in the green toolbard
5.  On the default 'click to add widgets' tab, scroll down to 'Card Decks'.
6.  Select `Custom Card Deck`.
7.  A circle will popup on the table, click 'Edit Collection'
8.  Select the gameplay options you'd like, then go to Cards, delete all existing cards.
9.  Select 'Import CSV file' 
10.  Upload `responses.csv` and 'prompts.csv' or any of the language versions you prefer. 
11.  Click `Done` to exit editing mode and go into gameplay mode
12. For any questions on how the layers work, see <https://playingcards.io/docs/custom-decks>

## Gameplay Instructions

The game can be both played in "Blitz" mode or "Debate" mode; each of these modes involve different settings.

1.  All players draw 5 white cards from their stack
2.  Click the spinner to choose the first player who will be the Card Czar.
3.  The Card Czar then pull a black prompt card and reads it to the group.
4.  All other players then put 1 white response card face down in their slot.
5.  The Card Czar then flips and reads each white card out loud.
6.  The Card Czar then picks one of the white cards to further discuss. +1 point goes to the player whose card was chosen, he is now considered as the winner of the round.
7.  The group then discusses further what else could go wrong based on the chosen card. At the end of the discussion an anonymous poll is launched and people award +1 point for the player who has the best arguments in discussion. 
8. The round winner also votes for his/her favorite among the 5 remaining players. If it matchs the community vote, this person  obtains an additional point as a reward since his point of view match the group's one. Each response has prompts to lead the discussion.
9.  The group's discussion for each round cannot exceed a certain time: 10 minutes for "Debate" mode, 5 minutes for "Blitz", to ensure a good flow.
10.  The player whose white response was chosen by the Czar, draws one challenge card and assigns the completion of the challenge to another player.
11. After the challenge, the next player becomes the Card Czar and clicks the "Deal" button. Each player then draws a new white card, so that they again have 5 cards in their hand.
12. The game ends when a player reaches : 8 points for "Debate" mode, 5 points for "Blitz" mode.

### During the game

1.  Take notes on ideas that you have not thought about before
2.  Some of the cards are causes, others are effects. Don't worry about what the game designers intended with each card, go where the discussion is best.
3.  Some of the cards may be upsetting. (Such as, a person is abused.)
4.  It's fine to take time to have discussion.
5.  Try not to get side tracked, though!

### Video Demonstration

[![What could go wrong card game demonstration](https://img.youtube.com/vi/DlqgWnhEqoc/0.jpg)](https://youtu.be/DlqgWnhEqoc)

## Adding new cards

Edit the `prompts.csv` and `responses.csv` to add new cards to the decks. Follow instrcutions for adding new cards here: <https://playingcards.io/docs/custom-decks>

## Suggested Citation

Nikolas Martelaro and Wendy Ju. 2020. What Could Go Wrong? Exploring the Downsides of Autonomous Vehicles. In *12th International Conference on Automotive User Interfaces and Interactive Vehicular Applications* (*AutomotiveUI '20*). Association for Computing Machinery, New York, NY, USA, 99--101. <DOI:https://doi.org/10.1145/3409251.3411734>

### Bibtex

`@inproceedings{10.1145/3409251.3411734,   author = {Martelaro, Nikolas and Ju, Wendy},   title = {What Could Go Wrong? Exploring the Downsides of Autonomous Vehicles},   year = {2020},   isbn = {9781450380669},   publisher = {Association for Computing Machinery},   address = {New York, NY, USA},   url = {https://doi.org/10.1145/3409251.3411734},   doi = {10.1145/3409251.3411734},   abstract = { While peer communities have the potential to support and improve our daily lives, there are also challenges and potential downsides to these practices. In this workshop, we intend to foster discussions about the potential negative aspects of online and peer communities in hopes of surfacing challenges that should be considered during the design process rather than after deployment. We will spur these conversations through a review of participant position statements and through group discussion facilitated by a card game called “What Could Go Wrong?” Our goal is to consider the collective creation model, improving technology, and reducing potential drawbacks. By identifying potential harms and downsides, the game players, and the community more broadly can design well-considered solutions.},   booktitle = {12th International Conference on Automotive User Interfaces and Interactive Vehicular Applications},   pages = {99–101},   numpages = {3},   keywords = {game with a purpose, failure modes, autonomous vehicles},   location = {Virtual Event, DC, USA},   series = {AutomotiveUI '20}.  }`

For some motivation on why we want to develop new hazard analysis games.

`@article{martelaro2022exploring,   title={Exploring Opportunities in Usable Hazard Analysis Processes for AI Engineering},   author={Martelaro, Nikolas and Smith, Carol J and Zilovic, Tamara},   journal={arXiv preprint arXiv:2203.15628},   year={2022} }`
