# OS X Tools

These are some useful tools I've written to help automate some tedious tasks in OS X.

## iTunes

### Clear Sort Entries.scpt

#### What does it do?

This is an AppleScript for iTunes that clears the *sort* entries for any tracks you choose. When the sort entries are clear, iTunes will use its automatic sorting so that *The Beatles* becomes *Beatles*, and such.

#### Why would I need this?

If your iTunes library ever gets corrupted, it is a real pain to clean it up and get the metadata right again. This is one of the tools I used to help with that.

#### How does it work?

Select some tracks, and then choose this script from the script menu. It's that icon that looks like a sheet of paper in the shape of an S.

#### How do I install it?

Drop it in **~/Library/iTunes/Scripts**.

Or, if you want to be fancy, keep this script in any folder you like, and then add a symbolic link to it in your iTunes scripts library. Open a terminal window, and type:

> ln -s ~/Library/iTunes/Scripts/Clear\ Sort\ Entries.scpt *path_to/Clear\ Sort\ Entries.scpt

#### How do I edit it?

Edit it using *Script Editor*. It should be the default app that OS X uses to open the file. These files aren't plain text, though, so you can't just use a regular text editor. 

#### Cool, thanks.

No problem. You doin' okay?

#### Yeah, not bad.

Right on. Have a good one.

#### You too.

Thanks.
