This project tries to outline a reproducible workflow that starts with the raw 
data and ends with the finished manuscript.

It is intended to be a live document that is updated over time. The latest version
will be stored on github.

# Intended audience #

This is mainly for my lab members. For relevant content, my lab is interested in
experimental psychology and cognitive neuroscience.

But other folks might find it useful also as a general way to organise a more
reproducible workflow.

# What's the easiest way to access the project? #

If you just want to read along, then hit the tutorial.html or tutorial.pdf file
and take a look.

If you want to see and work with the code, then:

1. Clone or download the project from github to your local machine.
2. Open the reproducible_workflow.Rproj file and renv() will automatically 
bootstrap itself.
3. renv() will then ask if you want use renv::restore() to install all of the
packages. Say yes.
4. At this point, you can use the project with the same package versions that were
stored in the renv.lock file.


