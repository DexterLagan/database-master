# Database Master
A small, simple tool to manage a MySQL database. Includes a decent query monitor with real-time explain and kill.

<p align="center"><img src="Screenshots/MainWindow.PNG"></p>

Several practical functions are hidden in the main menu, replicated in contextual menus available in each list-box. 'Export to CSV' and Excel are self-explanatory. 'Export to Scribble' is a more advanced feature which exports to Racket's Scribble documentation format. Scribble is a domain-specific language used to create application and language manuals. It outputs HTML and PDF through Latex.

<p align="center"><img src="Screenshots/Export-Options.PNG"></p>

Here is the configuration dialog, where you input your database settings :

<p align="center"><img src="Screenshots/Settings.PNG"></p>

One can specify which table prefixes to ignore, to hide them from the left-hand table list :

<p align="center"><img src="Screenshots/Preferences.PNG"></p>

This is the Query Tester window, that let you input queries and execute them. The results are displayed as table below :

<p align="center"><img src="Screenshots/QueryTester.PNG"></p>

The same window sports 'Explain' and 'Explain Advanced' buttons, which displays information about a query. Useful to troubleshoot and tune query performance :

<p align="center"><img src="Screenshots/Explain.PNG"></p>

Here is the Query Building window, used to generate queries visually :

<p align="center"><img src="Screenshots/QueryBuilder.PNG"></p>

FInally, the Query Monitor is an advanced tool which displays queries being executed on the server in real-time. The delay between list refreshes can be adjusted from 'Never' to 30 seconds. There are several fonctions available via context menus, such as 'Explain', which opens the selected query in the Query Tester window, and explains it, or 'Kill', which cancels the query thread - useful to kill queries taking too long.

<p align="center"><img src="Screenshots/QueryMonitor.PNG"></p>

Cheers,

Dexter
