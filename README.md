# northforceapps.com

User GitHub Pages site for **Northforce Apps**. This repo must be named
`NorthforceApps.github.io` (GitHub’s user-Pages convention). The `CNAME` file
binds the apex domain; project sites (`gpslogger`, `cue-loop`, `remotemic`,
`webcam`, `camerasudoku`) then appear at `https://northforceapps.com/<repo>/`.

Do not put a `CNAME` in those project repos.

Public URLs, canonicals and sitemaps are `https://northforceapps.com/...` only.
`https://northforceapps.github.io/...` 301s here and must not be linked. Search
Console uses the domain property `sc-domain:northforceapps.com`. After URL
Inspection shows Google’s canonical on this host, remove leftover github.io
URL-prefix properties from Search Console — they are measurement-only. Do not
re-create them.
