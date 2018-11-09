# Preact TodoMVC - With real-time updates

A modified version of [katopz' preact-todomvc-pouchdb example project](https://github.com/katopz/preact-todomvc-pouchdb).

I used code from [PouchDB's own TodoMVC guide](https://pouchdb.com/getting-started.html) to make this project work properly with real-time updates. With this version, if you open the todo page in two browsers/browser sessions and make changes to the todo list, the edits will immediately be shown in the other browser session, as long as you have a CouchDB server running and your demo page can connect to it properly.

Additionally, the "retry" option in the replicate.to/from initalization *should* make the page retry syncing if you lose network connection to internet or the CouchDB server, and then reconnect later. You should be able to test this by using the dev options in your browser to disable/enable internet connection on your own demo page.

I hope the code is correct and not using any wrong understandings of Preact or PouchDB/CouchDB, I'm currently learning Preact and PouchDB/CouchDB from scratch myself, so I barely have any idea what I'm doing.

* [Preact](https://preactjs.com/)
* [PouchDB](https://pouchdb.com/)
* [CouchDB](http://couchdb.apache.org/)
* [TodoMVC](http://todomvc.com/)
