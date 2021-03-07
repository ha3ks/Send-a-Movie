
# Send a Movie!


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger) 

Send an entire movie script line by line using this simple and short shell script. 

In my example, and because my son loves it, we are sending the script to 'The Bee Movie'.

# Requirements!

  - Macbook/Mac Desktop. This script only works with MacOS because of the built in messages app.
  - Target phone number must be using iMessage.
  
### Installation

- Clone this repo to your local machine. Open a terminal and copy & paste the below line of code 
 ```sh
$ git clone https://github.com/ha3ks/Send-a-Movie.git
```
- **NOTE**: Google "How to clone a github repository" if you are not familiar with this step.
 ```sh
$ cd Send-a-Movie
$ open autoMsg.sh 
```

### Setup
1. Open autoMsg.sh and change  ```targetBuddyPhone``` to your friend's phone number with area code I.e. +44 instead of '0' at the beginning for UK mobiles.
2. Open terminal and CD to where the script is stored. 
3. Use the following line of code to run the script. 
```sh
$ ./autoMsg.sh
```
-**NOTE**: you my have to change permissions on the file to run the script (google chmod file access).
### Customization
- Open  ```movieScript.txt``` in a text editor and replace the text with any movie script/text blurbs. 
}
