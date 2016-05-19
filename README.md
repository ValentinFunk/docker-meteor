# docker-meteor
Docker Image for compiling angular-meteor apps.

Basic Docker image but with a dummy app that is run during creation of the image to cache the meteor-tool version and package dependencies to speed up subsequent builds.
The packages file in the dummy app can be adapted to create images for any app.
