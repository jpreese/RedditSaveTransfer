﻿#Reddit Saved Post Transfer Tool#
By *MavisPuford*

Yeah, I know.  Creative name!  :)

##DESCRIPTION##

This tool lets you load up your saved posts from Reddit.  From there you can Export them to a HTML/CSV file, save them to another account, or get rid of them.  That's about it.

My main reason for creating this is that I have hundreds of saved posts, and I'm always like:  "Hey, I wanna look at all my r/food saved posts in one place."  I seem to compulsively save posts and never look at them again because I have to sift through pages of posts on reddit just to get to the one I need (and if I don't know what words were in the title, it's even harder to find).  So now I can export my r/food posts to an HTML file, open it up in my browser and look at them all in one place.  CTRL + F, "cinnamon".  There it is!

Another reason to use this tool is that reddit only saves 900-ish posts per user account.  So if you save posts all the time, you probably lose posts all the time if they aren't being saved somewhere else.

This is also nice for programs like Evernote, Onenote, whatevernote. Export all your saved posts from r/frugal, import them into whatever program you use, and you've got them all in a place where they are searchable and they won't be lost.

Or if I want to just have a Reddit account for r/food, I can create one and transfer my r/food saved links to that.  

You get the idea...

##INSTRUCTIONS##

First, put in your credentials and click Load Saved Posts.

After that, you can export the saved posts to a file (HTML and CSV), unsave them, or copy the posts to another Reddit account by putting in the credentials on the right and clicking Copy!

Checking Unsave from left account after saving unsaves the posts after they have been copied to the new account.

Checking Match selected rows transfers/exports only the posts that match the selected rows in the table.

Want to unsave just one post?  Just check Match selected rows, go to the post and select its id, then click Unsave.

**ALSO, IT TAKES A WHILE TO SAVE/UNSAVE POSTS.**

They have to be done one at a time, and Reddit's servers have limits on how often you can make requests (about one request every 2 seconds).

##SOURCE INFO##
Requires Microsoft .NET Framework 3.5.

You will also need to enable NuGet package restore which can be found in Visual Studio under "Tools > Options > Package Manager". Then you need to check "Allow NuGet to download missing packages during build".
