HttpRequester
=============
HttpRequester is a modified version of the excellent Poster add-on available for Mozilla Firefox.  

Originally developed by Tom Mutdosch

Distributed under the BSD License
http://www.opensource.org/licenses/bsd-license.php

<b>Usage overview</b>
<ul>
<li>Requests/responses transactions take place in a single application window.  
<li>A history of transactions is recorded (and kept across sessions).  You can view past requests, and re-execute them.  Selecting a transaction in the History list will show the full request/response.  
<li>For each transaction in the list, the request and response are shown, as well as the Elapsed Time and Content-Length  (The value used is the Content-Length response header if available, and the size of the response body otherwise.)
<li>Each column in the history list is resizable and re-orderable and can be hidden via the column picker. The ordering and width of each column are persisted.  
<li>Double-clicking a row in the history will show you a raw text version of the request and response
<li> You can edit raw requests by double-clicking a row in the history list, or clicking the Edit Raw Request button.  This is useful for easily viewing the request all at once, or for making quick tweaks to a previous request, such as adding or changing headers.  This is the same behavior as double-clicking a transaction in the transaction history list.
<li>You can press the Delete Request button to remove a selected transaction from history list.  (You can also hit the Delete key)
<li>Recent URLs, header names, and content types are remembered across sessions, and can easily be selected from drop-down lists.
<li>You can copy a request/response to clipboard for pasting into bug report, etc.  You can also copy existing requests from the clipboard by clicking the Paste Request button, and then executing the request. 
<li>Press the <Esc> key to close the HttpRequester window
<li>Save and load stored requests:  To save a request, click on a request in the history list and click Save Request.  You can optionally give the request a name.
<li>To load a request, click on Load Request - that will bring up a list of all saved requests.  You can select any request to load it into your history to view it, or you can click the Execute button to execute it immediately.
</ul>
<b>Advanced Preferences</b> (via about:config):
<code>extensions.httprequester.maxhistory - maximum number of requests to keep
extensions.httprequester.url.maxhistory - maximum number of URLs to keep
extensions.httprequester.contenttype.maxhistory - maximum number of content types to keep
extensions.httprequester.header.maxhistory - maximum number of header names to keep
extensions.httprequester.showAdvancedOptions  - set this to true to cause some of the other buttons to appear  (Google login, Save/Store/Import default URL/content type, timeout slider)
</code>

