
# Guillermo Dean's Landing Page

Welcome to Guillermo Dean's Landing Page! This page serves as a brief introduction to my professional background, hobbies, and links to my web development projects and some of my friends' projects. The landing page has gone through two revisions, and here's an overview of each version:

## 1️⃣First Revision (Node.js App in Docker Container)

The initial version of the landing page was built as a Node.js application running inside a Docker container. It was deployed on an AWS EC2 instance using PM2 as the process manager. This version served as a starting point to showcase my work and interests.

### Deployment Instructions:

1. Clone the repository.
2. Build the Docker image using the provided Dockerfile.
3. Run the Docker container and map the required ports.
4. Access the landing page via the public IP address or domain of the AWS EC2 instance.

![Static Badge](https://img.shields.io/badge/Guillermo-blue?logo=github&link=https%3A%2F%2Fgithub.com%2Fguillermodean%2FGuillermo)

## 2️⃣Second Revision (Astro Framework in AWS S3 Bucket)

The landing page has undergone a significant update in the second revision. I have reimagined the page using the Astro framework, taking advantage of its modern development features and performance benefits. To enhance the scalability and simplicity of deployment, the new version will be hosted on an AWS S3 bucket.

### Deployment Instructions:

1. Build the Astro application using the provided configurations.
2. Upload the generated static files to an AWS S3 bucket.
3. Configure the S3 bucket for public access and website hosting.
4. Access the landing page using the S3 bucket URL.

### 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```


### 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Contents of the Landing Page:

### Job Experience Description:

I will provide a concise overview of my professional experience, highlighting key achievements and skills in the web development industry.

### Hobbies:

Apart from my passion for coding and web development, I will share some of my hobbies and interests. This section aims to add a personal touch to the landing page.

### Links to Friends' Projects:

I believe in collaboration and supporting fellow developers. Therefore, I will include links to some exciting projects created by my friends. Feel free to explore their work and show them some love!

### Web Development Projects:

This section will showcase some of my web development projects. You can find links to live demos, GitHub repositories, and brief descriptions of each project.

## Contact Information:

If you have any questions, feedback, or opportunities, don't hesitate to contact me. You can find my contact details on the landing page.

Thank you for visiting my landing page! I hope you find it informative and enjoyable.


