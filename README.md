# Reproducibility_Demo

Specifying an R environment with a runtime.txt file
Jupyter+R: Binder

RStudio: Binder

Binder supports using R and RStudio, with libraries pinned to a specific snapshot on MRAN.

You need to have a runtime.txt file that is formatted like:

r-<YYYY>-<MM>-<DD>
where YYYY-MM-DD is a snapshot at MRAN that will be used for installing libraries.
