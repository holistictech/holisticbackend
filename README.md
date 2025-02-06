


<!-- PROJECT LOGO -->
<div>

<h1>Holistic Backend Service</h1>

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
        <li><a href="#prerequisites">Requirements</a></li>
        <li><a href="#installation">Installations</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This repo includes the main backend services.


### Built With

This project is built with the following technologies / frameworks :

* [![Docker][Docker]][Docker-url]
* [![Fastapi][Fastapi]][Fastapi-url]
* [![Python][Python]][Python-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Install Docker
  ```sh
  brew install --cask docker 
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Install Python Packages

* Install Pip
  ```sh
  python install pip  
  ```

* Install FastAPI
  ```sh
  pip install fastapi   
  ```

* Install Uvicorn Web Server
  ```sh
  pip install 'uvicorn[standard]'
   ```

* Install Multipart
  ```sh
  pip install python-multipart 
   ```

* Install Multipart
  ```sh
  pip install 'passlib[bcrypt]'  
   ```

* Run API
  ```sh
  uvicorn main:app --reload 
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Installation with Docker

  ```sh
docker build --no-cache -t fastapi-app .
   ```

  ```sh
docker run -d -p 80:80 fastapi-app
  ```


See API documentation on : http://localhost/docs
See Test API on : http://localhost/test



<!-- USAGE EXAMPLES -->
## Usage

Reach out to API documentation on http://127.0.0.1:8000/docs
Test dummy service on http://127.0.0.1:8000/test




<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/taskID`)
3. Commit your Changes (`git commit -m 'Insert a meaningful commit message here'`)
4. Push to the Branch (`git push origin feature/taskID`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Holistic Tech Group - [https://www.linkedin.com/company/holistic-tech-group/]

Project Link: [Holistic Backend](https://github.com/holistictech/holisticbackend)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Docker]: https://img.shields.io/badge/docker-0769AD?style=for-the-badge&logo=docker&logoColor=white
[Docker-url]: https://docs.docker.com/

[Fastapi]:https://img.shields.io/badge/fastapi-FFFFFF?style=for-the-badge&logo=fastapi&logoColor=green
[Fastapi-url]: https://fastapi.tiangolo.com/

[Python]:https://img.shields.io/badge/python-B0E0E6?style=for-the-badge&logo=python&logoColor=yellow
[Python-url]: https://www.python.org/