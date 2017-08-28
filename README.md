# TheGlue
Simplified search engine [Python 3.4] interfacing local SQL database [SQLite3] with GUI [PyQt5].

Information is stored in a separate database file.

The searching is handled with a mix of python and SQL.

'Documents' are retrieved from the database and translated to HTML for display purposes.


Goal: Connect numerous little pieces of information and make them searchable, so they can be found immediately
--------------------
[ policies, procedures, instructions, commands, methods, recipes, precedents, videos, docuements, spreadsheets, pictures, folders, etc. ]

Requirements:
*Minimal HTML knowledge (or just leave the auto-generated formatting code alone)
*Skill with a keyboard (this was not really designed for point-and-click although you could use it that way)

Author's notes:
I did what I could to make it possible to create, edit, and format 'documents'(web pages which are database entries) without any need for the user to have skill with HTML or CSS, although some code will display within the 'edit / create' window.

Everything was written in notepad and grows as my skill with Python/SQL/PyQT broadens.
The python script itself is far from a perfect example of best practices, but runs quite well, and has been very stable.

This was designed as an aid for a job that requires fast answers to questions regarding thousands of software suites, procedures, resources, guides, contacts, links, etc. 
I wrote this because I do not know of a better, keyboard-oriented, note-indexing application that could suit my needs. I started using 'the guide' http://theguide.sourceforge.net/ many years ago and liked it very much, but I wanted an application that was drastically different in a few ways; an app that had a strong emphasis on keyboard shortcuts and searching with a clear division between general knowledge articles and templates (where everything could be copied and pasted quickly and then sent to a client without the need for too much post-editing). I also ran into the problem where I would get search result hits for both templates and my own personal guides since they would have similar titles.

Uses: Note-taking and organizing notes in such a way that information can be found and recalled immediately.
--------------------
-Learning anything that requires frequent and fast reference to articles, theories, precedents [ how about coding? ]
-Aggregating large numbers of files / notes stored in various locations
-Linking to documents from various programs and websites

Excuses:
Since features are continually being added and / or changed, the integrated tutorial may not fully explain how to use the application to its full potential at this time. This application does not work well from USB, but does work portably.

Plans:
I plan on having the system automatically create a link for anything you drag and drop into the edit/create window.

Chris KC
2F0X.code@gmail.com
