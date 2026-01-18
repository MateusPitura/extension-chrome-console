<h1 align="center"> 
  <p>Star Console</p> 
</h1> 

<p> 
  <img src="https://img.shields.io/badge/Release-Dec%202024-green">  
  <img src="https://img.shields.io/badge/Version-0.1.7-blue">  
  <img src="https://img.shields.io/github/stars/MateusPitura/extension-typescript-console?style=social"> 
</p> 

## Description

View `console.log` outputs directly in your browser without needing to open the Developer Tools

A [VSCode](https://github.com/MateusPitura/extension-vscode-console) extension is available for optional use to enhance productivity

- [Features](#features)
- [How to Run](#how-to-run)
- [Technologies Used](#technologies-used)
- [Authors](#authors)

## Features 

🔔 **Snackbars:** displays `console.log` messages as snackbars on the web page

🔎︎ **Filter Logs:** filter the logs by those that start with an emoji 🌠

<p align="center"> 
  <video src="https://github.com/user-attachments/assets/bbecf63e-485b-49ad-9edf-99bfd149eeed"/> 
</p> 

## How to Run

1. On [GitHub](https://github.com/MateusPitura/extension-chrome-console), navigate to the Releases tab, download the `.zip` file, and unpack it

2. Open the Extensions tab in Chrome, enable `Developer mode` > `Load unpacked`

3. On `localhost`, you will see a button to hide and another to clear

4. When you print something using the emoji 🌠, it will appear as a snackbar

**For devs:**

1. Install packages with `npm i`

2. To test, run `npm run dev` and open `localhost:3000`

3. Open the Extensions tab in Chrome, enable `Developer mode` > `Load unpacked`, choose `dist/` folder

4. Update `version` references and run `npm i`

6. Run `npm run build`, zip the `dist/` folder with name `dist.zip`

7. Create a tag in Git and upload to GitHub

8. Create a new release on GitHub with the new `dist.zip` file

## Technologies Used

✔️ Typescript

## Authors 

| Mateus Pitura | 
|------| 
| <p align="center"><img src="https://avatars.githubusercontent.com/u/119008106" width="100" height="100"></p> | 
| <a href="https://www.linkedin.com/in/mateuspitura/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"> |
