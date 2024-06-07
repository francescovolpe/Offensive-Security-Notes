# logger++ filters



```json
[{"uid":"eda4681a-184f-439b-a145-45affea63b55","name":"RCE","filter":{"filter":"(Request.Parameters CONTAINS "cmd") OR (Request.Parameters CONTAINS "exec") OR (Request.Parameters CONTAINS "command") OR (Request.Parameters CONTAINS "execute") OR (Request.Parameters CONTAINS "ping") OR (Request.Parameters CONTAINS "Parameters") OR (Request.Parameters CONTAINS "jump") OR (Request.Parameters CONTAINS "code") OR (Request.Parameters CONTAINS "reg") OR (Request.Parameters CONTAINS "do") OR (Request.Parameters CONTAINS "func") OR (Request.Parameters CONTAINS "arg") OR (Request.Parameters CONTAINS "option") OR (Request.Parameters CONTAINS "load") OR (Request.Parameters CONTAINS "process") OR (Request.Parameters CONTAINS "step") OR (Request.Parameters CONTAINS "read") OR (Request.Parameters CONTAINS "function") OR (Request.Parameters CONTAINS "req") OR (Request.Parameters CONTAINS "feature") OR (Request.Parameters CONTAINS "exe") OR (Request.Parameters CONTAINS "module") OR (Request.Parameters CONTAINS "payload") OR (Request.Parameters CONTAINS "run") OR (Request.Parameters CONTAINS "print")"}},{"uid":"1151054a-5694-4c76-9328-fe11af81aa1b","name":"SSRF","filter":{"filter":"(Request.Parameters CONTAINS "dest") OR (Request.Parameters CONTAINS "redirect") OR (Request.Parameters CONTAINS "uri") OR (Request.Parameters CONTAINS "path") OR (Request.Parameters CONTAINS "continue") OR (Request.Parameters CONTAINS "url") OR (Request.Parameters CONTAINS "window") OR (Request.Parameters CONTAINS "next") OR (Request.Parameters CONTAINS "data") OR (Request.Parameters CONTAINS "reference") OR (Request.Parameters CONTAINS "site") OR (Request.Parameters CONTAINS "html") OR (Request.Parameters CONTAINS "val") OR (Request.Parameters CONTAINS "validate") OR (Request.Parameters CONTAINS "domain") OR (Request.Parameters CONTAINS "callback") OR (Request.Parameters CONTAINS "return") OR (Request.Parameters CONTAINS "page") OR (Request.Parameters CONTAINS "feed") OR (Request.Parameters CONTAINS "host") OR (Request.Parameters CONTAINS "port") OR (Request.Parameters CONTAINS "to") OR (Request.Parameters CONTAINS "out") OR (Request.Parameters CONTAINS "view") OR (Request.Parameters CONTAINS "dir")"}},{"uid":"da29b99e-0317-4a0e-84ee-ed44e69030ed","name":"XSS","filter":{"filter":"(Request.Parameters CONTAINS "q") OR (Request.Parameters CONTAINS "s") OR (Request.Parameters CONTAINS "search") OR (Request.Parameters CONTAINS "id") OR (Request.Parameters CONTAINS "lang") OR (Request.Parameters CONTAINS "keyword") OR (Request.Parameters CONTAINS "query") OR (Request.Parameters CONTAINS "page") OR (Request.Parameters CONTAINS "keywords") OR (Request.Parameters CONTAINS "year") OR (Request.Parameters CONTAINS "view") OR (Request.Parameters CONTAINS "email") OR (Request.Parameters CONTAINS "type") OR (Request.Parameters CONTAINS "name") OR (Request.Parameters CONTAINS "p") OR (Request.Parameters CONTAINS "month") OR (Request.Parameters CONTAINS "image") OR (Request.Parameters CONTAINS "list_type") OR (Request.Parameters CONTAINS "url") OR (Request.Parameters CONTAINS "terms") OR (Request.Parameters CONTAINS "categoryid") OR (Request.Parameters CONTAINS "key") OR (Request.Parameters CONTAINS "login") OR (Request.Parameters CONTAINS "begindate") OR (Request.Parameters CONTAINS "enddate")"}},{"uid":"61539c00-c0cb-4adf-9f13-b816ed43e3e7","name":"LFI","filter":{"filter":"(Request.Parameters CONTAINS "cat") OR (Request.Parameters CONTAINS "dir") OR (Request.Parameters CONTAINS "action") OR (Request.Parameters CONTAINS "board") OR (Request.Parameters CONTAINS "date") OR (Request.Parameters CONTAINS "detail") OR (Request.Parameters CONTAINS "file") OR (Request.Parameters CONTAINS "download") OR (Request.Parameters CONTAINS "path") OR (Request.Parameters CONTAINS "folder") OR (Request.Parameters CONTAINS "prefix") OR (Request.Parameters CONTAINS "include") OR (Request.Parameters CONTAINS "page") OR (Request.Parameters CONTAINS "inc") OR (Request.Parameters CONTAINS "locate") OR (Request.Parameters CONTAINS "show") OR (Request.Parameters CONTAINS "doc") OR (Request.Parameters CONTAINS "site") OR (Request.Parameters CONTAINS "type") OR (Request.Parameters CONTAINS "view") OR (Request.Parameters CONTAINS "content") OR (Request.Parameters CONTAINS "document") OR (Request.Parameters CONTAINS "layout") OR (Request.Parameters CONTAINS "mod") OR (Request.Parameters CONTAINS "conf")"}},{"uid":"24791f7a-ab95-4322-926b-9d413251b5e8","name":"SQLi","filter":{"filter":"(Request.Parameters CONTAINS "id") OR (Request.Parameters CONTAINS "page") OR (Request.Parameters CONTAINS "dir") OR (Request.Parameters CONTAINS "search") OR (Request.Parameters CONTAINS "category") OR (Request.Parameters CONTAINS "file") OR (Request.Parameters CONTAINS "class") OR (Request.Parameters CONTAINS "url") OR (Request.Parameters CONTAINS "news") OR (Request.Parameters CONTAINS "item") OR (Request.Parameters CONTAINS "menu") OR (Request.Parameters CONTAINS "lang") OR (Request.Parameters CONTAINS "name") OR (Request.Parameters CONTAINS "ref") OR (Request.Parameters CONTAINS "title") OR (Request.Parameters CONTAINS "view") OR (Request.Parameters CONTAINS "topic") OR (Request.Parameters CONTAINS "thread") OR (Request.Parameters CONTAINS "type") OR (Request.Parameters CONTAINS "date") OR (Request.Parameters CONTAINS "form") OR (Request.Parameters CONTAINS "join") OR (Request.Parameters CONTAINS "main") OR (Request.Parameters CONTAINS "nav") OR (Request.Parameters CONTAINS "region")"}},{"uid":"ebc0b526-60a0-412f-a1dc-8009c97777bc","name":"Open_Redirect","filter":{"filter":"(Request.Parameters CONTAINS "next") OR (Request.Parameters CONTAINS "url") OR (Request.Parameters CONTAINS "target") OR (Request.Parameters CONTAINS "rurl") OR (Request.Parameters CONTAINS "dest") OR (Request.Parameters CONTAINS "destination") OR (Request.Parameters CONTAINS "redir") OR (Request.Parameters CONTAINS "redirect_uri") OR (Request.Parameters CONTAINS "redirect_url") OR (Request.Parameters CONTAINS "redirect") OR (Request.Parameters CONTAINS "view") OR (Request.Parameters CONTAINS "image_url") OR (Request.Parameters CONTAINS "go") OR (Request.Parameters CONTAINS "return") OR (Request.Parameters CONTAINS "returnTo") OR (Request.Parameters CONTAINS "return_to") OR (Request.Parameters CONTAINS "checkout_url") OR (Request.Parameters CONTAINS "continue") OR (Request.Parameters CONTAINS "return_path") OR (Request.Path CONTAINS "/redirect/") OR (Request.Path CONTAINS "/cgi-bin/redirect.cgi") OR (Request.Path CONTAINS "/out/") OR (Request.Path CONTAINS "/out?") OR ((Request.Path CONTAINS "/login") AND (Request.Parameters CONTAINS "to"))"}}]// Some code
```