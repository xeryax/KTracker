KTracker is a new progress/stat tracker and reporting plugin for MUSHClient, specifically for Aardwolf
Currently, this plugin is based on a pup tracker unwillingly provided by Endymion, and heavily modified
to provide level tracking, gold tracking, pup tracking, quest tracking, etc.

The current version requires that you have the following plugins installed:
Bast:
broadcast_cp.xml
broadcast_double.xml
broadcast_kills.xml
broadcat_quest.xml

These are available directly from bast's repository along with his other plugins.
https://github.com/endavis/bastmush

This plugin will show you your pup times.  It will also
show reports of total pups, avg time/pup, slowest pup,
fastest pup, and interval averages.  The slowest pup for
each day is not used in averages, due to it likely being
an extended period of time since the last pup. 

  Command                   Purpose
------------------------------------------------------------------------------
  kt color <@x>        Set kt message color.
                         - standard mud colorcodes

  kt numcolor <@x>     Set numbers color.
                         - standard mud colorcodes
       
  kt accentcolor <@x>  Set brackets color.
                         - standard mud colorcodes       

  kt comm              Toggles commlog kt output.
  
  kt chan <chan>       Sets the output channel for each pup.
                         - No argument disables channel output.

  kt window            Toggles window kt output.
  
  kt avg <#>           Total for rolling average pup time.
  
  kt avg 0             Turns off display of average pup time.
  
  kt display           Toggle kt display between new and old style.
  
  kt help              Shows this message.

  kt days              Shows the current number of
                        days to keep daily pups.
  
  kt days <#>          Set the number of days to keep
                        daily kt totals.  Default 180.

  kt rep[ort] <#>      Show kt report for # of days.

  grep[ort] <chan>      Show today's gold report.  Channel optional.

  igrep[ort] <chan>     Show gold report since last clear.  Channel optional.

  igrep[ort] clear      Clear out the interval gold report data.
  
  kt info				Displays the options stored as variables

------------------------------------------------------------------------------
