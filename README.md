# Bleenco Styleguide For Developers

Note: This styleguide is not an exhaustive list of rules and processes. It is rather an emerging repository of habits that have proven to be something called "good software engineering practices". This repository can be modified at any time without any prior notification, if you want to stay on top of it please hit the star and follow updates.

The aim of this styleguide is to:
* inform guests on processes within Bleenco development team,
* brief new candidates and encourage them to submit their first pull request,
* remind current contributors what quality standard do we stand for.

## Table of Contents

- [Committing](COMMITTING.md)
- [Submitting](SUBMITTING.md)
- [Code of Conduct](https://github.com/bleenco/code-of-conduct/blob/master/CODE_OF_CONDUCT.md)

## <a name="rules"></a> Coding Rules
To ensure consistency throughout the source code, keep these rules in mind as you are working:

* All features or bug fixes **must be tested** by one or more specs (unit-tests, API tests).
* All public API methods **must be documented**.
* Abstruse **build must be green**

# Idea list for Google Summer of Codes 2019

* Abstruse: [WebPage](https://abstruse.bleenco.io), [Github page](https://github.com/bleenco/abstruse)
    Continuous Integration platform built with Node.js and Docker. Abstruse is a continuous integration platform requiring zero or minimal configuration to get started, providing safe testing and deployment environment using Docker containers. It integrates seamlessly with all git hosted services as GitHub, BitBucket, GitLab and gogs.
* bterm: [WebPage](https://bterm.bleenco.io), [Github page](https://github.com/bleenco/bterm)
    Fully customisable cross-platform terminal that works and feels the same way everywhere: MacOS, Linux and Windows.
* ng2-datepicker: [WebPage](http://ng2-datepicker.jankuri.com), [Github page](https://github.com/bleenco/ng2-datepicker)
    Angular 2+ Simple and minimal datepicker component
* semantic-depth-fusion: [WebPage](https://wangyida.github.io/publication/3dv18_wang/), [Github page](https://github.com/bleenco/semantic-depth-fusion)
    A direct reconstruction method to reconstruct from a 2.5D depth image to a 3D voxel data with both shape completion and semantic segmentation that relies on a deep architecture based on 3D VAE with an adversarial training to improve the performance of this task.
* bproxy: [WebPage](https://github.com/bleenco/bproxy), [Github page](https://github.com/bleenco/bproxy)
    Bproxy is a lightweight super-fast minimal-configuration proxy server written in C. It supports gzip compression and SSL out-of-the-box.
* bstats: [WebPage](https://user-images.githubusercontent.com/1796022/27514376-0014a7f0-5989-11e7-9ff2-06768014ef1e.png), [Github page](https://github.com/bleenco/bstats)
    Real-time server statistics dashboard, it is a server statistics built on top of RxJS.
* go-resumable: [WebPage](https://user-images.githubusercontent.com/1796022/32301133-e68eb2d2-bf5c-11e7-9f18-297c17facb7c.gif), [Github page](https://github.com/bleenco/go-resumable)
    Go library providing multiple simultaneous and resumable uploads.
* morose: [Webpage](https://morose.bleenco.io), [Github page](https://github.com/bleenco/morose)
    Private npm repository and/or proxy server for npmjs.org. morose allows you to have a local npm registry with zero configuration. You don't have to install and replicate an entire CouchDB database. morose keeps its own small database and, if a package doesn't exist there, it asks npmjs.org for it keeping only those packages you use.
