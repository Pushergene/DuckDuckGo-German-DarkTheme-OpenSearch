# DuckDuckGo-German-DarkTheme-OpenSearch
lets make duckduckgo less shit, 

Requirements:

about:config devtools.chrome.enabled

Download the .xml File, u can customize it. Open it in Firefox browser. While u are active in the .XML TAB, u must be in the tab! important!

Then u go to Web Developer -> Browser Console

u have to copy and paste this:

Services.search.addEngine(gBrowser.currentURI.spec, null, null, false);

