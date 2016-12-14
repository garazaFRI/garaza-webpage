# Webpage for Garaža FRI

Static HTML pages are generated with [Hugo](https://gohugo.io).

How to contribute:

1. fork repo
2. make branch 
3. change/update files
4. locally check output with

    $ hugo server --buildDrafts

5. submit Pull Request

We use [Drone CI](https://github.com/drone/drone), generated pages are published in https://github.com/garazaFRI/garazafri.github.io.
Drone uses custom Docker image https://hub.docker.com/r/matjazp/hugo-ci/.
