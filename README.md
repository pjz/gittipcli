
gittipcli
=========

A simple commandline to mess with gittip settings via the API.

Depends on: 
  * dopy (https://github.com/pjz/dopy) in your path
  * python packages from requirements.txt
  * GITTIP_USERNAME in your environment that contains your gittip username
  * GITTIP_AUTH in your environment containing your gittip auth token

For a list of commands, run 'gittip help'.  As of 2013-10-10, this results
in:

Commands:
--------
get_take <team> [<team> ...]
    get your take for the specified team(s).

help [cmd] - show either all the help or that of the specified command

set_take <team[=take]> [<team[=take]> ...]
    sets your take for the specified team(s).  If no take value is specified,
    increase your take the maximum amount for that team.

