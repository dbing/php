# Supported architectures

* linux/amd64
* linux/arm64

# Image Variants

## php:<version>-fpm

This variant contains PHP-FPM, which is a FastCGI implementation for PHP. See the PHP-FPM website for more information about PHP-FPM.

In order to use this image variant, some kind of reverse proxy (such as NGINX, Apache, or other tool which speaks the FastCGI protocol) will be required.

WARNING: the FastCGI protocol is inherently trusting, and thus extremely insecure to expose outside of a private container network -- unless you know exactly what you are doing (and are willing to accept the extreme risk), do not use Docker's --publish (-p) flag with this image variant.

# License

View license information for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in the repo-info repository's php/ directory.

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.