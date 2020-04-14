All match data in CSV format
============================

The background
--------------

As an experiment, after being asked by a user of the site, I started
converting the IPL data from YAML into the CSV format. This then expanded
to include international T20s, for both women and men, before, finally,
expanding again to cover all matches we provide.

This particular zip folder contains the CSV data for...
  All matches
...for which we have data, and is loosely based on the format that Retrosheet
uses for baseball, with some suitable hacks built in.

How you can help
----------------

Providing feedback on the data would be the most helpful. Tell me what you
like and what you don't. Is there anything that is in the YAML data that
you'd like to be included in the CSV? Could something be included in a better
format? General views and comments help, as well as incredibly detailed
feedback. All information is of use to me at this stage. I can only improve
the data if people tell me what does works and what doesn't. I'd like to make
the data as useful as possible but I need your help to do it.

Finally, any feedback as to the licence the data should be released under
would be greatly appreciated. Licensing is a strange little world and I'd
like to choose the "right" licence. My basic criteria may be that:

  * the data should be free,
  * corrections are encouraged/required to be reported to the project,
  * derivative works are allowed,
  * you can't just take data and sell it.

Feedback, pointers, comments, etc on licensing are welcome.

The format of the data
----------------------

Each file has a 'version', multiple 'info' lines, and multiple 'ball' lines.
'version' is just 1.3.0 for now, and will change as I make changes. The 'info'
entries should be fairly self-explanatory but feel free to ask on
Twitter (@cricsheet) if you're unsure. If you look carefully you may see some
slight hints as to some data we'll be including in the full data files in
the future.

Each 'ball' line has the following fields:

  * The word 'ball' to identify it as such
  * Innings number, starting from 1
  * Over and ball
  * Batting team name
  * Batsman
  * Non-striker
  * Bowler
  * Runs-off-bat
  * Extras
  * Kind of wicket, if any
  * Dismissed played, if there was a wicket

Full documentation of the CSV format will be added to the website in the
future, however if you would like to see it sooner feel free to get in
touch to let me know.

Further information
-------------------

You can find all of our currently available data at https://cricsheet.org/

You can contact me via the following methods:
  Email  : stephen@cricsheet.org
  Twitter: @cricsheet
