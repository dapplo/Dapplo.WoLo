# Dapplo.WoLo

This is just an idea:

Ever wanted to know what you did all day, when this was and how long it took?
Or maybe you need to write bills, or track time for your boss?
 
This project will support you by supplying an application which allows you to trackall things you do on your (Windows) PC, and write these to into a work log.

The idea is that the application can get information from many sources, and allow you to process these into "groups". The summarized information can be exported to multiple systems.

Examples of trackers:

* Windows session
** Login/Logout
** Lock/Unlock (from the UI/keyboard, or timeout / screensaver)
* Activity (mouse/keyboard)
* Active process (which window has focus)
** Title / Process location/name/id
* Active Window (focus / on top etc)
* Calendar (meetings)
* Email processing

The application should be easily extendible by addons/scripts, which can connect to the main process and supply information. Some examples:

* Track which JIRA ticket you are working on
* Track commits to a git repository (by using hooks)
* Get phonecall information from you telephone system (e.g. Fritzbox)

Export to different systems:

* Simple text files (CSV)
* Reports
* log work into a JIRA

The UI should make it possible to start & stop multiple times, and write short information on the current activity.

Maybe it is possible to create a "rule editor" which allows you to specify what processes mean what activity, e.g. when I work on a JIRA and use a certain application (eclipse) this belongs to the JIRA work.
