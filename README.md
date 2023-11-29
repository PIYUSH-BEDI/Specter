
<!-- PROJECT LOGO -->
<br />

  <h3 align="center">Specter</h3>

</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#manual-installation">Manual Installation</a></li>
        <li><a href="#binary-installation">Binary Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#docker">Docker</a>
      <ul>
        <li><a href="#tor">Tor</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

I've seen multiple projects out there in GitHub, that are crawlers for the deep web,
but most of them did not meet *my* standards of OSINT on the deep web.
So I decided to create my own deep web OSINT tool.


This tool serves as a reminder that the best practices of OPSEC should always be followed in the deep web.

<u>The author of this project is not responsible for any possible harm caused by the usage of this tool.</u>



---


---

Note:
 ⚠️ *PhoneNumber* module is currently not working.
Please do not use it as of now.
---


<!-- GETTING STARTED -->
## Getting Started


### Prerequisites

Before you can use our OSINT tool, please ensure you have the following dependencies installed:

1. **Docker: (optional)**
    -
You can download and install Docker
by following the official installation instructions for your specific operating system:
    - [Docker Installation Guide](https://docs.docker.com/get-docker/).

2. **Go: (required)**
    - [Golang Installation Guide](https://go.dev/doc/install).

3. **PostgresSQL: (required if you don't use docker)**
    - Make sure your .yaml environment variables matcht the environment in `docker-compose.yaml`
    - [PostgreSQL Installation](https://www.postgresql.org/download/)



![Data Preview](./web/static/data_preview.png)
![Data Preview 2](./web/static/data_preview2.png)

