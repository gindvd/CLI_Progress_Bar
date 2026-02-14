# CLI Progress Bar

## Description:
A simple progress bar rendered on the CLI.
Current iteration takes a percentage from script that loops
over thousands of files.

## How To Use:
Add file to directory with main script this will visually represent. 

Before the main loop of the script, create a class instance using foo = ProgressBar(). 
Then at the end of the loop, add foo.update(percentage). In the main script calculate 
the percentage by divide *num of loops* / *total* times 100.

The update call will update, then render the progress bar's track.
