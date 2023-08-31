# 🧮 Simple Calculator App

<p align = 'justify'>
A basic calculator web application built using Angular 16 and styled with Tailwind CSS. The app performs arithmetic operations and showcases the integration of frontend technologies. It's also deployed using Firebase hosting and Dockerized for easy deployment.
</p>

![Calculator Preview](https://github.com/suryanshsingh2001/Angular-Calculator/blob/main/src/screenshots/Screenshot%20(94).png?raw=true)

[Try Now](https://angular-calculator-2cc80.web.app/) 

## In a Nutshell ✨

- Addition, subtraction, multiplication, and division operations.
- Responsive design thanks to Angular 16 and Tailwind CSS.
- Easy deployment with Firebase hosting.
- Docker containerization for efficient deployment.

## Installation  🛠️

1. Clone the repository:

 ```bash
 git clone https://github.com/suryanshsingh2001/ang-calc.git
 ```

2. Install dependencies:
```
npm install
```

3. Make sure to be the ang-calc project directory

```
cd ang-calc
```

3. Run the development server:
```
ng serve
```

4. Open your browser and visit ```http://localhost:4200``` to see the calculator in action.

## Deployment 🌐
### Firebase Hosting
1. Make sure you have the Firebase CLI installed:

```bash
npm install -g firebase-tools
```

2. Build the project:

```bash
npm run build
```

3. Log in to your Firebase account:

```bash
firebase login
```
4. Initialize your Firebase project:

```
firebase init
```
5. Choose hosting and follow the prompts to deploy the app. 

<br>

## Docker 🐳
The project is dockerized for easy deployment and scalability. To run the app using Docker, use the following commands:

1. Build the image 
```
docker build --pull --rm -f "Dockerfile" -t angularcalculator:latest "."
```
2. Run image
```
docker run --rm -d -p 80:80/tcp angularcalculator:latest 
```

## Contributions 🤝

Contributions are welcome! Feel free to open an issue or submit a pull request.




---

Made with ❤️ by **Suryansh Singh**

[![Linkedin](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/suryansh-singh-473187235) 

 





