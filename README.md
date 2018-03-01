MoreVMs'18 Author Kit
=====================

This repository contains an adapted version of the `acmart` sigconf latex template.

Please see [sample-sigconf.tex](sample-sigconf.tex) for an example.

The desired license for the paper can be set with either
`\publicationrights{ccbyncnd}` or `\publicationrights{ccby}` right after
`\begin{document}`.

The main settings in the latex document should thus look roughly like this:

```
% Copyright
% \setcopyright{rightsretained}
% \setcopyright{ccbyncnd}
\setcopyright{ccby}


%Conference
\acmDOI{}
\acmISBN{}
\acmConference[MoreVMs'18]{Workshop on Modern Language Runtimes, Ecosystems, and VMs}{April 2018}{Nice, France}
\acmYear{2018}
\copyrightyear{2018}
```
