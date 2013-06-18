# Hello World

## The Rebase Test

We will be testing a rebase workflow here.

Here are some additional changes.



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