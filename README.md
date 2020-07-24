# docker-rver

Use [rocker-org/rocker-versioned](https://github.com/rocker-org/rocker-versioned) container image for base images.
Install some libraries and Change some configurations.

# Usage

```
docker run --rm -p 8787:8787 -e PASSWORD=yourpassword kotaroito/rstudio:3.6.3
```

# Development

```
cd rstudio
docker build -t kotaroito/rstudio:3.6.3 -f 3.6.3.Dockerfile .
docker push kotaroito/rstudio:3.6.3
```


# License
The Dockerfiles in this repository are licensed under the GPL 2 or later.

# Trademarks
RStudio and Shiny are trademarks of RStudio, PBC”

This project deploys RStudio products in unmodified form supplied by RStudio for internal use only.
[Automatic Permitted Use](https://rstudio.com/about/trademark/)
