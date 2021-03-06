# Contributing Everyone is welcome to contribute to this specification.

Any simple editorial contribution can simply be done with a GitHub Pull Request.
You can even do an inline edit of the file on GitHub.

For more substantial contributions that, please first start a thread in the
[sysapps mailing list](http://lists.w3.org/Archives/Public/public-sysapps/)  at
the W3C.

Note: The [System Applications Working Group](http://www.w3.org/2012/sysapps/)
operates under the [W3C Patent Policy which](http://www.w3.org/Consortium
/Patent-Policy-20040205/)  aims to enable implementations of W3C Recommendations
without the need to pay royalty fees. If you want to make contributions that can
be used in normative parts of our specifications, we require you to [make the
appropriate licensing commitments](http://www.w3.org/2004/01/pp-impl/58119/status).


# Style guide to contributors 

- the spec uses [ReSpec](http://dev.w3.org/2009/dap/ReSpec.js/documentation.html) 
- the spec is tidied using [HTML5 Tidy](https://github.com/w3c/tidy-html5). For
instructions on running HTML5 tidy, see below.  
- put comments in front of sections, for better readability with
  syntax coloring   editors


# Running HTML5 Tidy

Please make sure you have HTML5 tidy installed, instead of
the the one that  ships with *nix systems. You can comfirm this by running:

```bash 
tidy --version  #HTML Tidy for HTML5 (experimental) for ...
```
Once you have confirmed (make sure you have committed your changes before
running tidy, as the changes are destructive ... in a good way:)):

```bash 
tidy -config tidyconfig.txt -o index.html index.html
```
