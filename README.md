# One-Minute-Pitch

# Author
Lucy Chimoli

# Description
   
Pitches is a web application that allows users to use that one minute wisely. The users will submit their one minute pitch and other users will vote on them and leave comments to give their feedback on them. The pitches are organized by category. You can have different categories of pitches.
# User Stories
These are the behaviours/features that the application implements for use by a user.

As a user I would like to:
 user should see the pitches other people have posted.
user should view the different categories
user should vote on the pitch they liked and give it a downvote or upvote.
user should comment on the different pitches and leave feedback.
user should submit a pitch in any category.

## SetUp/Installation Requirements
PRerequisites
python3.8
pip
virtualvenv

# Cloning
In your terminal
 $ git clone https://github.com/chimolirgb/One-minute-Pitch
$ cd NewsPI

# Running the Application
 Creating the virtual environment
$ python3.8 -m venv --without-pip virtual
  $ source virtual/bin/env
  $ curl https://bootstrap.pypa.io/get-pip.py | python

  # Setting up the API key
   To be able to gather article info from the News API you will need an API Key.

  * In the root directory of the project folder create a file: start.sh
  * Insert the following info into it:

         
          python3.8 manage.py server

  * Insert the API Key you received from News Api where <Your-Api-Key> is

  # Testing the Application
   To run the test for the class files:
    $ python3.8 manage.py tests

    # Technologies Used
     python
     flask

    # License
    Copyright (c) 2021 Lucy chimoli