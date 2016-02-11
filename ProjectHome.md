## Purposes ##

Autopackage makes software installation on Linux easy.

Software distributed using Autopackage can be installed on multiple Linux distributions and integrate well into the desktop environment.

## About ##

This is Autopackage, the multi-distribution binary packaging framework for Linux systems.

Autopackage is stable, tested software that has been deployed by high profile projects. It has a strong commitment to backwards compatibility: your packages will continue to install as we add new features, although you may need to recompile them to get the new functionality.

It can resolve dependencies either from local files or from remote servers. It currently has simple support for package updates. It does not support integration with the native package manager although these features are planned for after the 1.0 release.

We also provide a collection of tools to let you build high quality portable binaries. The most important is apbuild, which is a drop-in build environment which creates binaries that work on older Linux distros by controlling glibc symbol versions, dependency scoping and correcting common distro portability mistakes. It includes relaytool which can be used to convert required dependencies into optional ones by automatically building dlopen/dlsym thunks.
Feature Hightlights

  * Build packages that will install on many different distros
  * Multiple front ends: best is automatically chosen so GUI users get a graphical front end, and command line users get a text based interface
  * Multiple language support (both in tools and for your own packages)
  * Automatically verifies and resolves dependencies no matter how the software was installed. This means you don't have to use Autopackage for all your software, or even any of it, for packages to successfully install.