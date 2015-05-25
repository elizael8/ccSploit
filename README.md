# ccSploit

<p>The script "<b>ccSploit.py</b>" affects two card shop scripts known as <b>"Vampire"</b> and <b>"Heaven"</b>.
<br>
<br>
This python script exploits two fraudulent "auto-selling" credit card shop sources.  Right now it can detect the source, test for an undiscovered SQL injection that affects all versions of the two sources, searches for vulnerable files, open directories, a backdoored version of the source, the possiblity of a default admin account, and even more that I'm too lazy to list.  The script is in its "pre-beta" stage, so sorry about some sloppy coding.  The main goal is to get it working in good order with lots of handy-dandy features first. 
<br>
<br></p>

<h4><a id="user-content-usage" class="anchor" href="#usage" aria-hidden="true"><span class="octicon octicon-link"></span></a>Usage</h4>

<hr>

<p><b>Regular usage:</b>
<br>
python ccSploit.py -u "url here"
<br>
<br>
<b>If the url is in a /shop/ directory then do:</b>
<br>
python ccSploit.py -u "url here" --shop
<br>
<br></p>

<h4><a id="user-content-important-notes" class="anchor" href="#important-notes" aria-hidden="true"><span class="octicon octicon-link"></span></a>Important Notes</h4>

<hr>

<ul>
<li>Built with Python 2.7. </li>
<li>Requires default libraries that come with Python, so no extra libraries required. </li>
<li>It is in its "pre-beta" stage, so please report ALL bugs.  It's not bug free.  I'm sure they're there. </li>
<li>Modifications are welcome to the code, but give credit for the original code please. </li>
</ul>

<p><br></p>

<h4><a id="user-content-upcoming-features" class="anchor" href="#upcoming-features" aria-hidden="true"><span class="octicon octicon-link"></span></a>Upcoming Features</h4>

<hr>

<ul>
<li>List import support.</li>
<li>Logging.</li>
<li>Debugging option.</li>
<li>Using POST SQL injection to actually exploit the SQL injection vulnerability.</li>
<li>Proxy support.</li>
<li>User-agent support.</li>
