It is likely that this will break with most releases of Mastodon. Contributions to new versions are welcome.

Contributions also sought to fine tune this layout for multiple widths (mobile, tablet, laptop etc)

Also thinking about adding vars with human-friendly naming so people can more quickly theme their instance, e.g.

:root {
  --main-bg-color: fff; 
  --main-text-color: 000; 
}

.column-header {background:var(--main-bg-color); color:var(--main-text-color);} 


