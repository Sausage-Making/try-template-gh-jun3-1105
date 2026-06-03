# ...project-title...

...description...

*[...author... &lt;...email...&gt;](mailto:...email...?subject=...project-name...)*


## Synopsis

... syntax of exposed function(s) / executable(s) and / or short explanation


## Parameters

... parameters of exposed function(s) / executable(s)


## Returns

... codes / states / data returned by exposed function(s) / executable(s)


## Examples

... example calls for exposed function(s) / executable(s)


## Demo

<!--???? Interactive use case(s) for exposed function(s) / executable(s) -->

<!-- ! HTML demo: dev vs. release switch
  * GitHub repo view does not render HTML, so a GitHub Pages view is linked
    * NB: GitHub Pages allows to maintain a single instance of the HTML demo file in the repo
  * In dev a GitHub Pages view would require a Pages build for any change to check instead of live reloading, so JavaScript is utilized here to detect a dev environment and reroute the link to the local repo instance
    * NB: JavaScript is stripped off in GitHub repo view
    * "dev environment" is defined by using "localhost" or a numerical ID as hostname 
      * NB RegEx: `.replace( /\d/g, '' ).replaceAll( '.', '' )` instead of `location.hostname.replace( /[\d\.]/g, '' )` to avoid `[]` which may mislead Markdown parsers to read it as link syntax
  * Unfortunately GitHub repo view displays "<script>" tags and their contents as literal content (for security), so the JavaScript here has to be pressed into an "onclick"
-->
See <a aria-description="Release vs. Dev switch = GitHub Pages vs. local file" href="https://...repo-owner....github.io/...project-name.../demo.html" onclick="if( location.hostname.replace( /\d/g, '' ).replaceAll( '.', '' ) === '' || location.hostname === 'localhost' ){ this.href='./demo.html'; alert( 'Dev environment detected - switching to local version' ); }">demo.html</a>


## Caveats

... things that may not work / not work as expected


## Installation

Pick for your preferred package manager:

```shell
  npm i ...repo-owner.../...project-name...
```

```shell
  pnpm i ...repo-owner.../...project-name...
```

```shell
  yarn add ...repo-owner.../...project-name...
```

```shell
  bun i ...repo-owner.../...project-name...
```


## Details

... for deeper understanding what the exposed function(s) / executable(s) and / or short explanation does / do


## References

<!--???? Sources to refer to in text by GFM Markdown internal links (cf. https://github.github.com/gfm/) -->

### ...authors...: ...title...
  * ...info-about-source...
  * ...https://url-for-source...

