# This is how you get started
<!-- Det nödvändigaste, installationer, viktiga kommandon -->

### Gem installation
In order to run the application you must install the necessary gems. In order to do so, navigate to the server folder within the server folder and type in the following command in the terminal:
```zsh
bundle install
```
All of the gems will be installed and the Gemfile.lock file will either be generated or installed.

### Github token installation
The app demands an github token to be in place. In order to get this to work, please create the .env file inside the server within server folder. Generate a token on your github profile (https://github.com/settings/tokens) and copy it. In the .env file, write the following 
```
PRIVATE_TOKEN = Your token here
```
but your token instead of "Your token here"

### Run application
In order to run the application, please type the following in the terminal while being in server within the server folder.
```zsh
rerun rackup
``` 
The application is now running on port 9292. 



