moodle-save-all-resources
=========================

<h3>Purpose</h3>
This script is meant to facilitate the downloads on a Moodle Class by adding a Download All button to every Session.

<h3>Features</h3>
<ul>
    <li>Single file download just by clicking on its link (default behavior is opening a new window)</li>
    <li>Download all files (trigger one by one) by clicking on the link <code>Download all</code></li>
    <li>Download all files zipped in an archive with folder useful structure  by clicking on the link <code>Download all zipped</code><br/>
    This option first fetches all the files an then creates the Zip archive. It marks with a green check sign the files successfully fetched. Marks with a red sign the files that are not downloadable which you should check out by yourself.
    </li>
    <li>Avoids the browser to open and render PDF files instead of downloading them.</li>
</ul>

<h3>Supported sites:</h3>
To be able to use this script in a Moodle installation you will have to add a @match tag with your installation base url.<br/>
<b>Sample:</b>
<code>@match   http://yourmoodleinstall.com/course/view.php*</code>

<h3>Notes:</h3>
<ul>
    <li>When using the <code>Download all</code> link the browser may popup an alert saying <em>This site is downloading multiple files</em> which you have to <em>Allow</em> otherwise the files are not downloaded.</li>
    <li>On PDF files the some browsers asky you to <em>Keep</em> or <em>Discard</em> before actually downloading.</li>
</ul>


<h3>How to install on Google Chrome</h3>
<ol>
    	<li>Download the <a href="../../raw/master/moodle-save-all-resources.user.js">moodle-save-all-resources.user.js</a> file on your computer.</li>
	<li>Open Google Chrome browser and go to the extension page at: 
	<a href="chrome://extensions/">chrome://extensions</a></li>
	<li>Simply drag and drop the ``moodle-save-all-resources.user.js`` file on this page.</li>
</ol>

<h3>How to install on Firefox & Other</h3>
<ol>
    	<li>Install the <a href="https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/">Greasemonkey</a> addon that will manage the script</li>
	<li>Go to <a href="../../raw/master/moodle-save-all-resources.user.js">moodle-save-all-resources.user.js</a>: Greasemonkey should open a dialog window to allow the script installation. Click *Install* and you're all set!</li>
</ol>


<h3>Supported browsers</h3>
<ul>
    <li>Chrome 14+</li>
    <li>Firefox 20+</li>
</ul>

<h3>Included plugins</h3>
<ul>
    <li>jQuery v1.10.2 <a href="https://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js">src</a></li>
    <li>multiDownload <a href="https://rawgit.com/sapeish/multiDownload/use-a-download/jquery.multiDownload.js">src</a></li>
    <li>jsZip <a href="https://rawgit.com/Trekky12/jszip/load-from-url/jszip.js">src</a></li>
</ul>

<b>Version:<b>1.1
<br/>
<b>License:<b>GNU General Public License (GPL)
