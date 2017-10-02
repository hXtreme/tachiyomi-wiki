**This page is for when you encounter a problem with a source (built-in or extension).**

It can be accompanied by these error messages:
* `HTTP Error 5xx`
* `HTTP Error 4xx`
* `java.security.cert.CertPathValidatorException`
* `Page List is empty`
* `Unable to resolve host`
* `unexpected url`
* `Attempt to invoke virtual method 'java.lang.String org.jsoup.nodes.Node.attr(java.lang.String}' on a null object reference`

# Diagnosis
1. Try opening the manga in browser. If there is CAPTCHA, solve it and see if it helped.
2. Change your internet connection ( wifi <--> mobile data or another wifi ), then try again.
3. Ask other users to try the action that gives you error.

If any of these help go to [It happens only to me](#it-happens-only-to-me).
If not, go to [Everyone is having this problem](#everyone-is-having-this-problem).

# It happens only to me
You may be getting a CAPTCHA, may have been IP-banned, or some other counter-measure that website owners deploy against programs like Tachiyomi. If that is the case, there is probably nothing that can be done about that. Some of them (like CAPTCHA) have to be manually solved, some are temporary (IP bans).

Workarounds that can lower chance of it happening again:
* Don't use downloads with the source
* Have less manga in library from the source

All of the above are very imprecise and fuzzy rules, because each site has their own, non-public limits and triggers.

# Everyone is having this problem
In this case it is a problem with the site.
1. Have a look at [open](https://github.com/inorichi/tachiyomi/issues) issues.
2. It may have been fixed already, but not released yet, so look at [closed](https://github.com/inorichi/tachiyomi/issues?q=is%3Aissue+is%3Aclosed) issues as well.
3. If you can't find the issue there, you can open a new one.