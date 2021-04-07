# Technical Test

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Development](#development)
- [Assessment](#assessment)
- [Demo](#demo)
  
## Getting Started

Follow the next instructions to get a copy of the project up and running in your local machine.

### Prerequisites

- Install Docker in your machine
    - Windows: https://docs.docker.com/docker-for-windows/install/
    - Mac: https://docs.docker.com/docker-for-mac/install/


### Installation

- Run the following commands:
```
git clone git@github.com:holdedhub/junior-frontend-challenge.git
cd junior-frontend-challenge
docker-compose up
```

### Development

Now your app will be available at [http://localhost:8000](http://localhost:8000).

You will be able to [log in](http://localhost:8000/wp-admin) with the following credentials:

- User: **holded-admin**
- Password: **admin-holded** 

## Assessment

We have a fresh Wordpress installation with the GeneratePress theme and GenerateBlocks plugin. We want to improve this
site with a Landing page with these blocks:
 
 - Header Section (check [Demo](#hero-section))
    - It's ok if the links are not pointing to any page
 - Hero Section (check [Demo](#hero-section))
 - Discover Section (check [Demo](#discover-section))
    - It has horizontal scrolling.
    - When you click an icon, it goes to the desired section.

Things to keep in mind:
 
 - Page needs to be responsive
 - We want to check your JS and CSS skills. You can create a custom Wordpress plugin, but we don't want you to use any
 plugin from the Wordpress directory.
 - Once you are done, publish your code in a private github repository.

Extra:
 - Add another Section using a Wordpress Plugin (from the wordpress directory).
 
## Demo

### Hero Section

![Hero Section](/docs/hero.png)

### Discover Section

![Discover Section](/docs/discover.gif)
