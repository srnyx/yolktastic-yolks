# Yolktastic Yolks

This fork of [pelican-eggs/yolks](https://github.com/pelican-eggs/yolks) was made to modify the Java
images to include the dependencies required for [Selenium WebDriver](https://www.selenium.dev/documentation/webdriver).

A curated collection of core images that can be used with Pterodactyl's Egg system. Each image is rebuilt
periodically to ensure dependencies are always up-to-date.

Images are hosted on `ghcr.io`.

All of these images are available for `linux/amd64` and `linux/arm64` versions, unless otherwise specified, to use
these images on an arm system, no modification to them or the tag is needed, they should just work.

## Contributing

When adding a new version to an existing image, such as `java v42`, you'd add it within a child folder of `java`, so
`java/42/Dockerfile` for example. Please also update the correct `.github/workflows` file to ensure that this new version
is tagged correctly.

## Available Images

### [Java](/java)

Includes the required dependencies for [Selenium WebDriver](https://www.selenium.dev/documentation/webdriver).

* [`java8`](/java/8)
  * `ghcr.io/srnyx/yolktastic-yolks:java_8`
* [`java11`](/java/11)
  * `ghcr.io/srnyx/yolktastic-yolks:java_11`
* [`java16`](/java/16)
  * `ghcr.io/srnyx/yolktastic-yolks:java_16`
* [`java17`](/java/17)
  * `ghcr.io/srnyx/yolktastic-yolks:java_17`
* [`java19`](/java/19)
  * `ghcr.io/srnyx/yolktastic-yolks:java_19`
* [`java21`](/java/21)
  * `ghcr.io/srnyx/yolktastic-yolks:java_21`
* [`java22`](/java/22)
  * `ghcr.io/srnyx/yolktastic-yolks:java_22`
