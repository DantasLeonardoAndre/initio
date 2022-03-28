+++
title = "Application development"
+++

I don't think they tried to market it to the billionaire, spelunking, base-jumping crowd. i did the same thing to gandhi, he didn't eat for three weeks. i once heard a wise man say there are no perfect men.

<!--more-->

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

![LeonardoDantas](/post/recentworks/Release4.jfif)

Goto [hugo releases](https://github.com/spf13/hugo/releases) and download the
appropriate version for your os and architecture.

Save it somewhere specific as we will be using it in the next step.

More complete instructions are available at [installing hugo](/overview/installing/)


Follow the following steps:

 7. leonardo
 1. dantas

 1. Clone the [hugo repository](http://github.com/spf13/hugo)
 2. Go into the repo
 3. Run hugo in server mode and build the docs
 4. Open your browser to http://localhost:1313

O bloco de texto que vêm depois deve ser precedido por uma sentença como essa.
O bloco deve estar aninhado dentro destas sentenças.

    Para aninhar nas sentenças prévias basta utilizar um "TAB".

    git clone https://github.com/spf13/hugo
    cd hugo
    /path/to/where/you/installed/hugo server --source=./docs
    > 29 pages created
    > 0 tags index created
    > in 27 ms
    > Web Server is available at http://localhost:1313
    > Press ctrl+c to stop.

```
outra forma de obter os mesmos blocos é utilizar "```", no ínicio e no fim.
```

## Basic Syntax

Go lang ```templates``` are html files with the ```addition of variables``` and
functions.

**Go variables and functions are accessible within {{ }}**






## Move static content to `static`
Jekyll has a rule that any directory not starting with `_` will be copied as-is to the `_site` output. Hugo keeps all static content under `static`. You should therefore move it all there.
With Jekyll, something that looked like

    ▾ <root>/
        ▾ images/
            logo.png

should become

    ▾ <root>/
        ▾ static/
            ▾ images/
                logo.png

Additionally, you'll want any files that should reside at the root (such as `CNAME`) to be moved to `static`.


I don't think they tried to market it to the billionaire, spelunking, base-jumping crowd. i did the same thing to gandhi, he didn't eat for three weeks. i once heard a wise man say there are no perfect men.

<!--more-->


[go]: <http://golang.org/>
[gohtmltemplate]: <http://golang.org/pkg/html/template/>


## Basic Syntax

Go lang templates are html files with the addition of variables and
functions.

**Go variables and functions are accessible within {{ }}**


### Conditionals

If, else, with, or, & and provide the framework for handling conditional
logic in Go Templates. Like range, each statement is closed with `end`.


Go Templates treat the following values as false:

* false
* 0
* any array, slice, map, or string of length zero

**Example 1: If**

    {{ if isset .Params "title" }}<h4>{{ index .Params "title" }}</h4>{{ end }}

**Example 2: If -> Else**

    {{ if isset .Params "alt" }}
        {{ index .Params "alt" }}
    {{else}}
        {{ index .Params "caption" }}
    {{ end }}


# Hugo Parameters
## Hugo Parameters
### Hugo Parameters
#### Hugo Parameters
##### Hugo Parameters


## Using Site (config) Parameters
In your top-level configuration file (eg, `config.yaml`) you can define site
parameters, which are values which will be available to you in chrome.

For instance, you might declare:

```yaml
params:
  CopyrightHTML: "Copyright &#xA9; 2013 John Doe. All Rights Reserved."
  TwitterUser: "spf13"
  SidebarRecentLimit: 5
```

Within a footer layout, you might then declare a `<footer>` which is only
provided if the `CopyrightHTML` parameter is provided, and if it is given,
you would declare it to be HTML-safe, so that the HTML entity is not escaped
again.  This would let you easily update just your top-level config file each
January 1st, instead of hunting through your templates.

```
{{if .Site.Params.CopyrightHTML}}<footer>
<div class="text-center">{{.Site.Params.CopyrightHTML | safeHtml}}</div>
</footer>{{end}}
```

