# docker-complexheatmap

Docker image for the [ComplexHeatmap](https://bioconductor.org/packages/release/bioc/html/ComplexHeatmap.html) BioConductor package.

These images are tagged by the maftools version number.
For more information, please see [the Docker Hub page](https://hub.docker.com/r/docker/ningyuan/complexheatmap).

## Development

Some notes for myself:

- Build this image by passing the Dockerfile through `STDIN`: `docker build -t ningyuan/complexheatmap:2.8.0 - < Dockerfile`.
  This way, there will be no build context (which is a good thing).
- Tag and release this GitHub repository with each new Docker tag.
  This is just good practice.
