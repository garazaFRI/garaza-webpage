# Webpage for Garaža FRI

Static HTML pages are generated with [Hugo](https://gohugo.io).

How to contribute:

1. Fork repo
2. Create branch 
3. Change/update files
4. Locally build the site to check the output:
    ```bash
    $ hugo server --buildDrafts --buildFuture
    ```
5. Submit Pull Request

We use [Drone CI](https://github.com/drone/drone), generated pages are published in https://github.com/garazaFRI/garazafri.github.io.
Drone uses custom Docker image https://hub.docker.com/r/matjazp/hugo-ci/.
