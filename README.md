# Mobile Application for School Gamification

[![Classpip Badge](https://img.shields.io/badge/classpip-mobile%20application-blue.svg)](https://github.com/classpip/classpip)
[![license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/classpip/classpip/blob/master/LICENSE)

[![classpip-icon](https://github.com/classpip/classpip/raw/master/resources/icontext-land.png)](http://www.classpip.com/)

[Classpip](https://www.classpip.com) is a software architecture for teachers and students to perform school gamification activities inside the school environment through different platforms such as mobiles, tablets and computers.

The software architecture is composed by a [mobile application](https://github.com/classpip/classpip-mobile) for performing “quick” class activities oriented to teachers and students. For “long” operations such as deep into reports and setup the platform there is an [administration dashboard](https://github.com/classpip/classpip-dashboard) accessible from every computer. These two pieces shares the information through a [service-oriented architecture](https://github.com/classpip/classpip-services) that exposes the main methods for data manipulation. Besides, the software architecture will provide and open [website](https://github.com/classpip/classpip-website) for marketing and publicity purposes.

[![classpip-arch](https://github.com/classpip/classpip/raw/master/images/project-architecture.png)](http://www.classpip.com/)

All the project is supported for some open-source tools to configure an agile environment combined with a [continuous integration](https://travis-ci.org/classpip) system for [continuous deployment](https://hub.docker.com/u/classpip/) on different platforms.


## Repositories

The classpip architecture is composed by a set of repositories, here you can find the status of all this repositories and theire README's.

| Name | URL | Travis CI | Docker | Codacy |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| [![Classpip Badge](https://img.shields.io/badge/classpip-mobile-brightgreen.svg)](https://github.com/classpip/classpip-mobile) |  | [![Build Status](https://travis-ci.org/classpip/classpip-mobile.svg?branch=master)](https://travis-ci.org/classpip/classpip-mobile) |  | [![Codacy Badge](https://api.codacy.com/project/badge/Grade/65b8b3d1b7234b14b6d05db424ce6f09)](https://www.codacy.com/app/classpip/classpip-mobile?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=classpip/classpip-mobile&amp;utm_campaign=Badge_Grade) |
| [![Classpip Badge](https://img.shields.io/badge/classpip-dashboard-brightgreen.svg)](https://github.com/classpip/classpip-dashboard) | [admin](http://admin.classpip.com) | [![Build Status](https://travis-ci.org/classpip/classpip-dashboard.svg?branch=master)](https://travis-ci.org/classpip/classpip-dashboard) | [![Docker Pulls](https://img.shields.io/docker/pulls/classpip/classpip-dashboard.svg?maxAge=2592000)](https://hub.docker.com/r/classpip/classpip-dashboard/) | [![Codacy Badge](https://api.codacy.com/project/badge/Grade/c0bc305863284f0a8478cbd963615f44)](https://www.codacy.com/app/classpip/classpip-dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=classpip/classpip-dashboard&amp;utm_campaign=Badge_Grade) |
| [![Classpip Badge](https://img.shields.io/badge/classpip-website-brightgreen.svg)](https://github.com/classpip/classpip-website) | [web](http://www.classpip.com) | [![Build Status](https://travis-ci.org/classpip/classpip-website.svg?branch=master)](https://travis-ci.org/classpip/classpip-website) | [![Docker Pulls](https://img.shields.io/docker/pulls/classpip/classpip-website.svg?maxAge=2592000)](https://hub.docker.com/r/classpip/classpip-website/) | [![Codacy Badge](https://api.codacy.com/project/badge/Grade/6d3b729cd3bc4949b9445a717878761e)](https://www.codacy.com/app/classpip/classpip-website?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=classpip/classpip-website&amp;utm_campaign=Badge_Grade) |
| [![Classpip Badge](https://img.shields.io/badge/classpip-services-brightgreen.svg)](https://github.com/classpip/classpip-services)  | [api](http://api.classpip.com) | [![Build Status](https://travis-ci.org/classpip/classpip-services.svg?branch=master)](https://travis-ci.org/classpip/classpip-services) | [![Docker Pulls](https://img.shields.io/docker/pulls/classpip/classpip-services.svg?maxAge=2592000)](https://hub.docker.com/r/classpip/classpip-services/) | [![Codacy Badge](https://api.codacy.com/project/badge/Grade/bc7f317bf0fd4c83a81a8dd00346dce1)](https://www.codacy.com/app/classpip/classpip-services?utm_source=github.com&utm_medium=referral&utm_content=classpip/classpip-services&utm_campaign=Badge_Grade) |


## License

Classpip is released under the [Apache2 License](https://github.com/classpip/classpip-mobile/blob/master/LICENSE).
