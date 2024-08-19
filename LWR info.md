1. layoutTemplate behaviour.
Eg. lwr.config.json info will always takes presidence over content md files. 
if no lwr configs then content md files are in considaration. 

2. layout chaining layoutTemplate doesn't work. 

Ability to define parent/base layout from child

Eg. Base.njk >> Blog.njk

Here we want to refer base.njk as parent for blog.njk we can't do that. 

Note: we can refer nav.njk in base.njk but not vise-versa. 
"https://www.11ty.dev/docs/layout-chaining/"

3. Deep merge data check? 

4. Front matter in Markdown.
When it comes to context objects, Markdown templates are a little different from HTML and Nunjucks templates. Context isn't passed into Markdown templates unless you use a route handler, which is a way of customizing the page response. "Route Handler Functions" in Server-Side Routing in LWR discusses this advanced topic.


5 Apex Module:
https://salesforce.stackexchange.com/questions/401688/how-can-we-resolve-salesforce-apex-modules-in-a-standalone-lwr