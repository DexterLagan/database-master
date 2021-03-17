# Database Master
A small, simple tool to manage a MySQL database. Includes a decent query monitor with real-time explain and kill.

<img src="Screenshots/MainWindow.PNG">

Here is the configuration dialog, where you input your database settings :

<img src="Screenshots/Settings.PNG">

One can specify which table prefixes to ignore, to hide them from the left-hand table list :

<img src="Screenshots/Preferences.PNG">

This is the Query Tester window, that let you input queries and execute them. The results are displayed as table below :

<img src="Screenshots/QueryTester.PNG">

The same window sports 'Explain' and 'Explain Advanced' buttons, which displays information about a query. Useful to troubleshoot and tune query performance :

<img src="Screenshots/Explain.PNG">

Here is the Query Building window, used to generate queries visually :

<img src="Screenshots/QueryBuilder.PNG">

FInally, the Query Monitor is an advanced tool which displays queries being executed on the server in real-time. The delay between list refreshes can be adjusted from 'Never' to 30 seconds. There are several fonctions available via context menus, such as 'Explain', which opens the selected query in the Query Tester window, and explains it, or 'Kill', which cancels the query thread - useful to kill queries taking too long.

<img src="Screenshots/QueryMonitor.PNG">

Cheers,

Dexter
