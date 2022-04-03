# My CV

## Contacts

I am originally from St. Petersburg, Russia, but currently out of the country for political and moral reasons.

1. Telegram: [p_vasilev](https://t.me/p_vasilev)
2. E-mail: [explosere@gmail.com](mailto:explosere@gmail.com)

## About me

- Have experience with Go Language, as well as several other programming languages and toolsets
- Flexible, quick learner
- Passionate about software development: at work, I write code for the project; after work, I write code for the fun of it
- Influenced and improved the process of software development in different ways, introducing automated static analysis tools, good engineering practices whenever there was such a need
- Took initiative in discussions regarding the aforementioned improvements
- Have a good command of written and spoken English (С1 according to EPAM's internal English assessment)

## Education

### Saint Petersburg State University, 2016

*B. Sc., Applied Mathematics and Control Processes*

## Professional experience

### Go Software Engineer, EPAM

*St. Petersburg, Remote, Jan 2018 - Present*

Outsourcing work for the following projects:

- ### Backend for a Swiss reinsurance company

  *May 2021 - currently*

  A backend service that provides data aggregation, transformation, and search

  Responsibilities:

  - Supported the existing infrastructure
  - Performed major architectural overhauls to improve system stability, code readability, and ease of debugging
  - Automated several engineering processes, such as:
    - client library generation from an OpenAPI spec
    - version management for generated clients
    - CI checks for outdated Swagger specs & generated code
    - a self-linting, self-documenting Makefile

  Technologies and services used:

  - Go, [echo], Docker, Kubernetes, OpenAPI/swagger ([swagger-codegen], [goswagger]), Elasticsearch, Redis, RabbitMQ, Azure Cloud, Azure DevOps

- ### MongoDB Kubernetes Atlas Operator

  *Dec 2020 - Apr 2021*

  A [Kubernetes Operator] for managing [MongoDB Atlas] clusters, a future-proof replacement for OSBv1 & [OSBv2](#user-content-mongodb-atlas-open-service-broker-v2) in more modern and widely used environments

  Responsibilities:

  - Built the product from the ground up as part of a small team
  - Participated in product design
  - Performed manual testing
  - Worked on unit, integration, and end-to-end tests
  - Provided expertise in MongoDB Atlas API and best practices for implementing client software for said API

  Technologies and services used:

  - Go, Ginkgo, Docker, Kubernetes ([kubebuilder], [controller-gen], [Operator SDK]), MongoDB, [MongoDB Atlas]

- ### MongoDB Atlas Open Service Broker v2

  *Jul 2020 - Jan 2021*

  An [Open Service Broker] for managing MongoDB Atlas clusters from CloudFoundry, a more flexible replacement for AOSB v1

  Responsibilities:

  - Built a product conforming to the OSB API *almost* from the ground up as the main developer
  - Took a major part in product design
  - Directly assisted corporate clients with the product, including support calls & incident recovery on multiple occasions
  - Contributed enhancements & bug fixes to dependencies during development
  - Assisted with test automation, CI/CD

  Technologies used:

  - Go, Pivotal/VMWare stack ([CloudFoundry/Tanzu][CloudFoundry], [Concourse CI]), Docker, MongoDB, [MongoDB Atlas], [MongoDB Realm], [Sentry]

- ### Pivotal CloudFoundry Tile for MongoDB clusters

  *May 2019 - Sep 2020*

  A [CloudFoundry Tile] for managing MongoDB Ops Manager clusters from CloudFoundry

  Responsibilities:

  - Supported existing CF Tile product until retirement as the main developer
  - Implemented various improvements to stability, security and versatility of the product
  - Took a major part in improving CI/CD workflows and other QOL enhancements
  - Developed more resilient reconciliation algorithms for syncing state between the Tile and MongoDB Automation Agents

  Technologies used:

  - Go, Pivotal stack ([CloudFoundry], [Concourse CI], [BOSH], etc.), Docker, MongoDB, [MongoDB Ops Manager]

- ### Video Platform Backend

  *Jan 2018 - Apr 2019*

  Backend work for a streaming/on-demand video platform

  Responsibilities:

  - Helped migrate legacy Ruby codebase to Go in a backwards-compatible fashion
  - Participated in all stages of the product development lifecycle, from inception to retirement
  - Developed and maintained high-load distributed systems (with the help of Kubernetes, high-speed clustered Redis cache backend, and Varnish HTTP accelerator)
  - Performed manual functional and integration testing
  - Created functional and integrational tests for automated testing of multiple products
  - Implemented multiple access management solutions (using encryption, plain JWT, and OAuth)
  - Proposed and supported the implementation of several "good engineering practices," such as Git Flow, commit and PR size policies; actively participated in improving the engineering process

  Technologies used:

  - Go, Docker, MySQL/MariaDB, Kubernetes, Redis, Memcached, Consul, Datadog, PagerDuty, Sumologic

---

### C++/C# Software Engineer, Takeprofit Technology

*St. Petersburg, Aug 2016 - Dec 2017*

Development of various financial tools for brokers (Forex, exchanges, etc.). Automated money management, risk management, trade handling

Responsibilities:

- Developed new software solutions from the ground up
- Enhanced existing products with requested features
- Participated in refining the development process by integrating common practices such as code reviews, static code analysis with automatic reports, more effective git flow-like branching model
- Led the development process on several occasions
- Provided support for existing code
- Took part in conformance testing and communication with clients on technical matters regarding

Technologies used:

- C++, WinAPI, STL, Boost, C#, PostgreSQL, MySQL, SQLite, WinForms, WPF

---

### Software Developer (C++), Robomoika

*Remote, part-time, Nov 2015 - Jul 2016*

Building an automated car washing system from the ground up

Responsibilities:

- Developed a system that controls several stepper motors, rotors and water sprinklers
- Implemented algorithms for distance measurements, modelling and visualization of washed objects or vehicles, camera calibration, path prediction, JS/QML scripting
- Took part in emulating a real-world prototype for testing and refinement of used algorithms

Technologies used:

- C++, STL, Qt 5, QML, OpenCV, OpenMP, Javascript

---

### Junior Software Developer (C++), Lanit-Tercom

*St. Petersburg, part-time, Sep 2015 - Feb 2016*

Working on image processing system for geodesic needs

Responsibilities:

- Implemented various image conversion, comparison, enhancement and processing algorithms
- Assisted in adding support for HDR imaging to legacy code
- Provided support for existing code

Technologies used:

- C++, STL, Boost, OpenCV

---

### Trainee Software Developer (C++), Lanit-Tercom

*St. Petersburg, Jun 2015 - Aug 2015*

Algorithms for quadcopter control

Responsibilities:

- Took part in implementing algorithms for object detection and control of a loaded quadcopter

Technologies used:

- C++, STL, Qt 4, Qt 5, OpenCV

## Hobbies & interests

### Passionate hobbyist developer

I write code for all sorts of stuff without considering whether it would be useful for anything at all.
Some examples of things I wrote:

- a primitive operating system in [MASM]
- a formula parser for university studies
- a Monkey programming language parser, interpreter & VM compiler (following ["Writing An Interpreter In Go"](interpreterbook.com) & ["Writing A Compiler In Go"](https://compilerbook.com) two-part book by Thorsten Ball)
- a revised Monkey-like language parser & native x86 compiler using [GNU Flex], [GNU Bison] & LLVM
- a Minecraft-like voxel rendering engine/game (a 3D game in Go!)
- a pseudo-3D (Duke Nukem 3D, Doom 1 style) game with support for non-euclidean level geometry that runs on an [ESP32]
- a [Bell 202] modulator/demodulator that runs on an Arduino (makes the old-fashioned modem noises)
- software for an [APRS] ([Bell 202] + [AX.25]) ham radio weather station

### Electronics enthusiast

I like building cool things from electronic components that, again, aren't necessarily meant to be useful.

Some examples of things I built:

- a schedule-based camera with live YouTube streaming for watching my pet cockatiel
- a [Bell 202] [AX.25] serial sound modem
- an [APRS] ham radio weather station powered by an Arduino and a pocket radio
- an ATmega programmer powered by an Arduino
- multiple simple AM and FM radio receivers
- an FM radio transmitter
- a flower watering system with humidity sensor, Wi-Fi, and remote web access powered by an ESP-32
- a simplistic WAV player powered by an Arduino
- an LED-activated buzzer attachment for my washing machine to indicate that the washing cycle has finished or that user input (i.e., adding fabric softener) is required

### Less nerdy activities

I also like to play video games, cook, go camping, occasionally play guitar and bass, and write music.

[Kubernetes Operator]: https://kubernetes.io/docs/concepts/extend-kubernetes/operator/
[CloudFoundry tile]: https://docs.pivotal.io/tiledev/2-6/tile-basics.html
[Open Service Broker]: https://www.openservicebrokerapi.org/
[Sentry]: https://sentry.io/
[BOSH]: https://bosh.io/
[Concourse CI]: https://concourse-ci.org/
[MongoDB Atlas]: https://www.mongodb.com/cloud/atlas
[CloudFoundry]: https://www.cloudfoundry.org/
[MongoDB Realm]: https://www.mongodb.com/realm
[MongoDB Ops Manager]: https://www.mongodb.com/products/ops-manager
[kubebuilder]: https://kubebuilder.io/
[controller-gen]: https://book.kubebuilder.io/reference/controller-gen.html
[Operator SDK]: https://sdk.operatorframework.io/
[GNU Flex]: http://gnuwin32.sourceforge.net/packages/flex.htm
[GNU Bison]: https://www.gnu.org/software/bison/
[APRS]: http://www.aprs.org/
[MASM]: https://www.masm32.com/
[ESP32]: https://www.espressif.com/en/products/socs/esp32
[Bell 202]: https://en.wikipedia.org/wiki/Bell_202_modem
[AX.25]: http://www.ax25.net/
[swagger-codegen]: https://github.com/swagger-api/swagger-codegen
[goswagger]: https://goswagger.io/
[echo]: https://echo.labstack.com/
