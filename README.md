# Task Killer
The purpose of this application is a quick fix for my parents. Running certain
games on their computer, they do not close properly and they become unable to
open them again later. The task never shuts down fully. This application is
intended to close the application, with each application having its own forced
close. Saves them having to go and do a reboot each time a game doesn't close.

For use, change the notepad.exe section to the actual exe that fails to close,
and then simply run the .bat file anytime the application doesn't shut down
properly. This batch script is intended to be run as a one application kill per file.

# Use Case Example

Someone without much, or any computer experience or knowledge has an application that they need to close to be able to create another running instance of it. Previously, they may have closed the application, but it didn't fully exit and still exists within the Task Manager as a running task. The running application(s) need to be closed before another instance of the application can be ran. A knowledgeable user goes in and copy and pastes this code into a .bat file, in a place the end user can easily access. Any extra kill commands are added by simply copy and pasting the single TaskKill like and adding in an additional application, or adding in an extra variable if desired. The .bat as mentioned is stored in an easy to use location for the end user, as it may be required an unknown number of times in the future, as the application(s) sometimes stick in Task Manager indefinitely - until ended, or a system is rebooted. The end user doesn't know what the application actually does, simply that if they receive an error saying the the application they wish to run is already running, they simply run the necessary .bat file from the Desktop, or whatever easy to access location was decided upon, which to them, simply allows them to run their application as they initially intended.
