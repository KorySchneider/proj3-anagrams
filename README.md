# proj3-anagrams
_Kory Schneider_

_CIS 322, Fall 2016_

## What is this?
This is a simple vocabulary anagrams game for primary school English language learners (ELL).

## Installation
Clone the repository:

    $ cd where/you/want/it
    $ git clone https://github.com/koryschneider/proj3-anagrams
    $ cd proj3-anagrams

Then set it up and run it:

    $ bash ./configure && make service

## Usage
`$ make service` will start a Green Unicorn (gunicorn) server, which is more suitable for running over a long period of time.

`$ make run` will launch the server in debugging mode.

`$ make test` will run the test suite.

## Gameplay
When you start the game, you will be given a list of words, and a list of jumbled letters. Your goal is to spell three words (amount can be changed in CONFIG.py) from the list of letters. When a matching word is typed, it is added to the list of found words.

## Credit

Forked from Michal Young at https://github.com/UO-CIS-322/proj3-anagrams for CIS 322: Intro to Software Engineering.
