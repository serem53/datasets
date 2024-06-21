<p align="center">
  <a href="https://www.tinytotos.com/" target="blank">
    <img src="https://www.drkfoundation.org/wp-content/uploads/2018/08/Tiny-Totos-new-logo.jpg" width="400" style="max-height: 100px;" alt="Tiny Totos logo" />
  </a>
</p>

# Tiny Totos API

Welcome to the Tiny Totos main API! This powerful API enables seamless interaction with Tiny Totos' data, enhancing daycare services and operations.

## Description

Tiny Totos is dedicated to transforming childcare in Kenya and beyond by providing daycare managers with a platform to ensure ease of operation and deliver affordable, high-quality services. Our API supports a wide range of functionalities, from managing daycare operations to enhancing parental engagement.

## Features

- **Authentication module**: Securely manage user authentication, ensuring that only authorized personnel have access to the platform's features.
- **Daycare module**: Oversee and manage all daycare operations, creating new daycares,updating existing daycares, viewing daycares either by id or all and deleting daycares.
- **Children module**: Efficiently enroll and manage children's records, including personal details, medical information, and enrollment status.
- **Organization module**: Handle organization-level settings and configurations, ensuring that all daycare centers under the organization adhere to standardized policies and procedures.
- **Cohorts module**: Create and manage cohorts or groups of daycares, enabling tailored activities, curriculum planning, and progress tracking for specific groups or needs.
- **Guardian module**: Create, update, and manage guardian details, including contact information, relationship to the child, and emergency contacts.
- **Revenue module**: Monitor and manage financial aspects of the daycare, including fee collection, billing, and financial reporting to ensure sustainable operations.
- **Attendance module**: Keep track of daily attendance effortlessly, providing accurate records of children's attendance for administrative and safety purposes.
  
## Installation

To get started with the Tiny Totos API, you need to have Node.js and git installed. Follow the steps below to set up the API on your local machine.

in your terminal run the following commands:
## cloning repository
```bash
$ git clone https://github.com/TinyTotos/mtoto_core-nest.git
```

enter the cloned repository
```bash
$ cd mtoto_core_nest
```

## Running the app

install dependencies
```bash
npm isntall
```
 development
 ```bash
$ npm run start
```
watch mode
```bash
$ npm run start:dev
```

production mode
```bash
$ npm run start:prod
```
## Running tests

 unit tests
 ```bash
$ npm run test
```

e2e tests
```bash
$ npm run test:e2e
```

 test coverage
 ```bash
$ npm run test:cov
```

# ORM and CONTAINERISATION
The Tiny Totos API uses Prisma as its ORM (Object-Relational Mapping) tool for database interactions. Additionally, we have dockerized the application for easier deployment. To run the application using Docker, ensure you have Docker installed and then execute:
```bash
$ docker-compose up -d
```
This command will create and run the containerized application from the defined image in the docker file.

## Contributors

This project is maintained by the following contributors:

- MaxWell Iragu  
- Baraka Mulumia 
- Benard Kimiri
- Trevor Serem
- Steve Ouko

## License

This project is licensed under the MIT License. See the [MIT](./LICENSE) file for more details.

## Contact

For inquiries about Tiny Totos or support with the API, please contact us:

- **Email**: info@tinytotos.com
- **Website**: [www.tinytotos.com](https://www.tinytotos.com)
  

Feel free to reach out to us with any questions or feedback.

---

For detailed documentation on using the Tiny Totos API, refer to [docs](https://tinytotos.atlassian.net/wiki/spaces/MW/pages/18055171/Mtoto-Web+SAAS+Architecture).


