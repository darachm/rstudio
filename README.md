This repo is munged from @nickjer 's nice two part build of a rstudio server.

So go there for a sane build.
This is slapped together because I gotta teach and don't want to have 3.6.3 and
rstudio on my main system....

Build as

    sudo singularity build rstudio.img Singularity.3.6.3

Or just pull from shub

    sudo singularity run shub://darachm/rstudio:3.6.3
