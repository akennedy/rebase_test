# Hello World

## The Rebase Test

We will be testing a rebase workflow here.

Here are some additional changes.

These changes are being applied at master

These changes are being applied at master

These changes are being added via master feature
> 
>    master 
> 
>     |\
>     | \
>     |  \       #########
>     |    ------#develop#
>     |          #########
>     |              | 
>     +---rebases--->|
>     |              |
>     |              |           ##########
>     |              +--branch-->#FEATURE1#
>     |              |           ##########
>     |              |              |       ##########
>     |              +-------branch-------->#FEATURE2#
>     |              |              |       ##########
>     |              |              |            |
>     +---rebases--->|              |            |
>     |              +-----rebases->|            |
>     |              +--------------|-rebases--->|
>     |              |              |            | Features are done, code review occurs here.
>     |              |<-merge squash+            |
>     |              |<---------merge squash-----+
>     |              |
>     +---rebases--->|
>     |              |
>     |<-merge sq.---+
>     |
>     |
>     |

Here is feature 3

These changes are being added from feature2

These are also feature 2 changes
