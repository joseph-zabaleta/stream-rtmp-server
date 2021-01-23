# Stream Project RTMP Server

## Table of Contents

---

-   [Overview](#overview)
-   [Installation](#installation)
-   [Authors](#authors)
-   [Collaborations](#collaborations)
-   [License](#license)
-   [Acknowledgements / Resources](#acknowledgements-/-resources)

---

## Overview

This is a Real Time Message Protocol (RTMP) Server and is built to support another project. The main project repo is here [Stream Project](https://github.com/joseph-zabaleta/streams-client)

## Installation

RTMP server makes use of the npm package `node-media-sever` please follow the code block below to get started.

```bash
git clone https://github.com/joseph-zabaleta/stream-rtmp-server.git
cd stream-rtmp-server
npm install
```

Now you are ready to start up the local RTMP server

```bash
npm start
```

By default this server runs on HTTP port 8000, RTMP port 1935. These can be adjusted inside the `index.js`. Please refer to the following documentation on how to use `node-media-server` for which streaming platform you plan to use for local use.

## Authors

-   Software Developer: Joseph Zabaleta
    -   [Official Github](https://github.com/joseph-zabaleta)

## License

This project is under the MIT License.

## Acknowledgements / Resources

-   [Modern React with Redux](https://www.udemy.com/course/react-redux/)
-   [node-media-server Docs](https://github.com/illuspas/Node-Media-Server)
