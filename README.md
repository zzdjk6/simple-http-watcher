simple-http-watcher
===================

like httpfox,but it's for chrome.


TODO:

* 302 request share the same requestId,I can log every header sending now,but then I should update it,
but I can't use requestId now,I think I should block redirect request and make another.
* catch all infos when redirect/complete/error,and update all the infos with them.
* clear log.
* stop log.
* search domain:when filtering,it should still can update datagrid with url matches search pattern.
* I also wan't filter log by Method/code/type.
* think of refactoring this program into MVC pattern in the future.