# Docker: Nginx and NODE

Services container infrastructure integrated by NGINX and NODE, designed to implement applications made with Vue.js or Node under a microservices structure. In consequence, the backend enviroment must be deploy from other service container.

## Description

This project is a simple container services infrastructure designed to deploy applications made with Vue,js or Node. It is integrated by:

- NGINX
- NODE

As a developer looking to improve my skils and abilities in the domain of the Vue.js framework, I share this container structure in interest of making it easier to deploy both development and production environments.

## Getting Started

### Dependencies

Docker Compose relies on Docker Engine, so make sure you have Docker Engine installed. For more information related to the installation process, check the [official Docker page](https://docs.docker.com/compose/install/).

### How to use

1.  Navigate to the main github page of the repository
2.  Above the file list, click **Use this Template** to [create a new github repository from this template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template)
3.  Clone your new repository
4.  If you want, you can customize the names of your services, replacing the patterns "\_service" by "\_app_name", replacing the matches found in ./docker-compose.yml.
5.  From your local copy and under app directory:
    1. Run `npm install -g @vue/cli`
    2. Run `vue create . `
    3. Run `docker-compose up -d --build`

<!--
 ### Executing program

 * How to run the program
 * Step-by-step bullets
 ```
 code blocks for commands
 ```

 ## Help

 Any advise for common problems or issues.
 ```
 command to run if program contains helper info
 ```

 ## Authors

 Contributors names and contact info

 ex. Dominique Pizzie
 ex. [@DomPizzie](https://twitter.com/dompizzie)
-->

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
