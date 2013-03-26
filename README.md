# mynt-docs

This repo contains the source files of the [mynt website][mynt].


### Viewing locally

To view mynt's website locally, install mynt, clone this repo, and then generate the site using mynt. This can be done by issuing the following commands:

    $ pip install mynt
    $ cd <some directory>
    $ git clone https://github.com/Anomareh/mynt-docs.git && cd mynt-docs/
    $ mynt gen _build/ && mynt serve _build/

You can then view it by browsing to [http://localhost:8080/][server].

_Do note, the mynt website makes use of the font [Envy Code R][envy-code-r] of which I am not able to distribute. Please install it locally if you wish to view the website as intended._


[envy-code-r]: http://damieng.com/blog/2008/05/26/envy-code-r-preview-7-coding-font-released
[mynt]: http://mynt.mirroredwhite.com/
[server]: http://localhost:8080/
