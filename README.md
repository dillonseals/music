# music
Tool for musicians


Idea
Create a functional web application usable by musicians to help them create music


Purpose
Complete a project using highly in-demand skills for my resume/portfolio


Features
 - users can create an account & login/logout
 - users can create, edit, and delete tunes
 - users can share tunes with other users
    - users can set permissions on shared tunes (view, comment, and edit)
 - users can PM other users
 - users working on a tune together can group chat in real time

Tune Creation Features (the technical, interesting stuff)
 - users set a key on creation
    - key able to be changed later
    - auto-transcription
 - jazz chords
    - chords auto-suggested based on key and location in the tune
    - default I-ii-V-I (or minor equivalent)
    - program suggests possible insertions and substitutions
 - voice-leading?
    - extensions, alterations, and general chord choices could perhaps be informed by voice-leading
    - this may be quite ambitious to implement, but we'll see


Thoughts

Database
 - create a table with each note, then assign notes as FKs to each key (mode?) table
 - somehow need to track relationships between different chords
    - how to know that G is V of C, but also I of G, etc

Front-End
 - 