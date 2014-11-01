####Instructions

1. Select a target. You may use The Hacker Academy website, your own company, or any large organization of your choice.
2. Go to [Google](http://www.google.com) and use the `site:victim.com` query (filling in your own target for **"victim.com"**) to find all indexed content in the primary website.
3. Record any useful information.
4. Note any nonstandard subdomains with webservers on them.
  * Subdomains such as "dev", "content", "members", "admin" or "forums" may contain interesting targets.
  * If the results contain mostly "www" subdomains (or any other subdomain), repeat the search with
  ```
  site:victim.com -site:www.victim.com
  ```
  * You can continue to add further modifiers as needed to find the greatest variety of information.
5. Note website filesystem conventions.
  * What is the folder structure for the application? This information may be useful in guessing the location of unindexed features to attack.
  * How is the website organized?
  * What extension (html, php, asp, etc.) do most files have?
  * Where is user-uploaded content stored?
  * What programming languages are used? Files with a .php extension use PHP, .asp use ASP, etc.
  * Are different programming languages used on different subdomains? This would signify a wider variety of servers and server-side technology used by IT staff.

This concludes the lab exercise.
