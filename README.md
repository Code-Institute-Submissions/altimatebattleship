![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome,

This is the Code Institute student template for deploying your third portfolio project, the Python command-line project. The last update to this file was: **March 14, 2023**

## Reminders

- Your code must be placed in the `run.py` file
- Your dependencies must be placed in the `requirements.txt` file
- Do not edit any of the other files or your code may not deploy properly

## Creating the Heroku app

When you create the app, you will need to add two buildpacks from the _Settings_ tab. The ordering is as follows:

1. `heroku/python`
2. `heroku/nodejs`

You must then create a _Config Var_ called `PORT`. Set this to `8000`

If you have credentials, such as in the Love Sandwiches project, you must create another _Config Var_ called `CREDS` and paste the JSON into the value field.

Connect your GitHub repository and deploy as normal.

## Constraints

The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.

---

Happy coding!


<h1>altimatebattleship</h1>

<p>A Python programing languege game that is all about hitting the ships of your oponent while your openent is also trying to do the same thing.</p>

<h1>How is it played</h1>

<p> The player need to enter their name and press enter and two boards will be randomly generated.  The player will be able to see their ships, labelled by @ sign.  The player will not be able to see the oponents ships, ie. the computer's in this case.   Guesses are marked by X for a miss and by * for a hit.  The player and  the computer will take turns in trying to locate the openents ship.  Tha one that will manage to kill all of the oponents sheep will win. otherwise the game will need to be restarted after four attempts.</p>

<h1>Features</h1>

<p> ships are randomly distributed on the respective boards. and the player cannot see the computer's ship.</p>

<img src="/workspaces/altimatebattleship/initialized_boards.JPG">

<h1>Bugs<h1>
<p>No time to figute out the error handling of a string instead of a number. Lost many days due to Mall functioning of Codes spaces infrastructure<\p>

<h1>References<h1>

Anna Greaves
The code is inspired by the Love Sandwiches Code Institute walkthrough Project videos delivered by Full Stack Web developer and content creator, Anna Greaves.

Matt Rudge
The CSS code on the footer was partly taken from the battle ships game walk through project presented by Matt Rudge, Senior Product Developer at code institude.