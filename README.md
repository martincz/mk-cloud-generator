mk-cloud-generator
========================

The MoKee OpenSource contributors cloud scripts.

> To generate the code, open a linux console and type:
> 
>    ./generate_mk_wordcloud.sh
> 
> This will fetch all MoKee OpenSource repos (around 61Gb), parse the commits
> logs, mix the data and generate a cloud.zip in the output
> folder. This will take look long time the first time.
> 
> The file resources/well-known-accounts.txt was left willfully empty. The
> format of this file should match the name of the account and the list
> of known emails for the account
>
>      Name on Gerrit|nick|email1|email2|...

This project is based in a modified version of the
[kumo](https://github.com/kennycason/kumo) library.

Copyright © 2015 The MoKee OpenSource Project
