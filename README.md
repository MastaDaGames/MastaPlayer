Building the project yourself for Android tutorial:

1: Import the project Into Godot and export It for
android making sure the permissions- "Read External 
Storage" & "Read Media Audio" are both checked. Also
when exporting make sure to uncheck the box that says
"Export With Debug".

2: Using something like MT Manager first you need
to open the apk then tap "classes.dex" and open with
"Dex Editor plus" find the names of the smali files
you need to modify (aka the ones In Patches.7z) Then
for each one just delete everything In them and replace
them with the contents of the txt files making
sure to save everything. Now simply sign the
apk then Install It and your done.
