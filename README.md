<h1>Bloc Jams - A jQuery-Driven Music Player App</h1>

<h4>Refactored an existing code base using jQuery to make a fully functional music play that displays album information and standard music controls for playing, pausing, skipping forward/backward, and adjusting the volume.</h4>

<ul>The Bloc Jams Music Player includes the following features:
<li>A list of the album's songs.
<li>Regardless of scroll position, there is a visible "player bar" with controls for Play/Pause, Previous Track, Next Track, Seek, and Volume.</li>
<li>The play/pause button shows a "play" icon if there no song is playing.</li>
<li>The play/pause button shows a "pause" button if a song is playing.</li>
<li>The previous track and next track buttons only respond when a song is playing.</li>
<li>The previous track button plays the previous song on the album.</li>
<li>The previous track button doesn't respond if there is no previous song.</li>
<li>The next track button plays the next song on the album.</li>
<li>The next track button doesn't respond if there is no next song.</li>
<li>There is a slider that shows the current time position of the song.</li>
<li>The position of the current song can be changed by clicking and dragging on the time control slider.</li>
<li>There is a slider that shows the player's current volume.</li>
<li>The volume can be adjusted by clicking and dragging on the slider.</li>
</ul>

![bloc jams 1](https://user-images.githubusercontent.com/33248170/53693247-0e90ab80-3d9e-11e9-9de4-9829ca658bb1.png)

This project highlighted the pros and cons to both jQuery and DOM (Data Object Model) scripting, depending on the circumstance.  Since jQuery is a front-end development library, it is made to be easy to interact with the DOM because it is a collection of JavaScript code that is wrapped in a simpler function.  It provides shortcut methods to perform tasks quicker with less lines of code.  It does not have any external dependencies and is easy to add to a project.  It is generic and can be used to accomplish a purpose of many goals.  This makes jQuery very convenient.  “Vanilla” DOM scripting is JavaScript in its purest form - so anything that jQuery can do, DOM can be used.  There are many methods to select elements - hence why jQuery was created (to simplify it).  The good part is that it requires no libraries and can also contribute to open source projects.  A benefit of DOM is that external packages are easier to include in a project if they don’t depend on other external packages, like jQuery.  jQuery is convenient because it is a wrapper that creates a smooth and convenient browser experience that works consistently in all the major browsers.  However because of the extra code, an older browser may not run jQuery as well, since it adds weight to the site and slows things down.  Luckily, older browsers will still have access to the content, just not the same layout or features.  Because one of jQuery’s main benefit is to simplify the code, this is also one of the main reasons that “vanilla” DOM scripting can be better - the code that jQuery wraps up, is a lot and could be important and useful.
