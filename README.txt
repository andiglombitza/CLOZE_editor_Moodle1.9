INSTALLATION

1. Unzip
2. copy the contents of the folder clozeeditor to your moodleroot directory, keeping the directory structure

The following files in your installation will be overwritten with mod'd files from the Moodle 1.912 standard package (so make sure to BACK THEM UP):

lib/weblib.php *
lib/editor/htmlarea/htmlarea.php
lib/editor/htmlarea/dialog.js

* Overwriting weblib.php is OPTIONAL:

If you choose to include this modified weblib.php, the CLOZE-editor button will only show for teachers, and only in question-interfaces. In any other editor instances, and for students, it will be hidden.

If you refrain from overwriting weblib.php, it will still work, but the editor button will be visible in EVERY editor instance for teachers, but not for students.