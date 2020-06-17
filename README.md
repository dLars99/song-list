# Song List

This is a practice exercise for NSS Book 2, Supplemental 5. The purpose is to create code in jQuery to fulfill the requests set forth in the exercise, as follows:

Attach a click handler to the button with jQuery. When
the button is clicked, use $.ajax() to load `songs.json`
from the file system


Chain a `.then()` method to the ajax call, and when
it is complete build a DOM component for each song with
the following structure. Use the jQuery append() method
to put an HTML representation of each song the DOM as a
child component of the .