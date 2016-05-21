# freelance
This is a slim cli script for administrating freelance hours.

##Installing
To use this script you need two things installed; 
 - php5 / php7
 - the php extension for sqlite3
If you're using Linux Ubuntu you can install these dependencies using the terminal: `sudo apt-get install php7.0 php7.0-sqlite3`. Now I recommend you placing this script in your `home/bin` folder in order to use it globally.

##Usage
- Inerting a new hour: `freelance -i [project] [hours] [notes]`
- Inserting a new hourly rate: `freelance -r [project] [rate] [currency]`
- Get a list of all the hours: `freelance -l`
- Retreive a csv file of the db: `freelance -csv > "output.csv"`.

##Todo
 - Feature: delete hours.
 - Feature: check if all projects have a rate when displaying lists
