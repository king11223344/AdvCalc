
# AdvCalc

AdvCalc is a web application built using React.js and styled using Tailwind CSS. It is a static website that serves as an efficient calculator with almost all the features of a scientific calculator. Additionally, it offers three different themes that users can choose from based on their preferences.

## Installation

To install and run the AdvCalc project locally, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/king11223344/AdvCalc.git
```

2. Navigate to the project directory:
```bash
cd AdvCalc
```

3. Install the dependencies:
```bash
npm install
```

## Usage

To start the AdvCalc web app, use the following command:

```bash
npm run start
```
This command will run the app in development mode. Open http://localhost:3000 in your browser to view it.


## Deployment on GitHub Pages
AdvCalc can be easily deployed on GitHub Pages using the gh-pages package. Here's a step-by-step guide:

1. Install the gh-pages package as a dev dependency:
``` bash
npm install gh-pages --save-dev
```
2. Open the package.json file and add the following lines:
```bash
"homepage": "https://your-username.github.io/AdvCalc",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```
3. Build the optimized production version of the app:
``` bash
npm run build
```
4. Deploy the app using the following command:
```bash
npm run deploy
```
5. Wait for the deployment process to finish. Once completed, you can access your AdvCalc web app at the URL specified in the homepage field.
   
## Themes
AdvCalc offers three different themes to enhance the user experience. Users can choose their preferred theme by following these steps:

Open the AdvCalc web app.

Look for a theme toggle or a settings icon on the interface.

Click on the toggle or icon to display the available themes.

Select the desired theme from the options provided.

The chosen theme will be applied instantly, providing a visually appealing calculator experience.

## Contributing
Contributions are welcome! If you find any bugs, have suggestions for improvements, or want to add new features, please open an issue on the GitHub repository or submit a pull request.

When contributing to this project, please ensure that you follow the code of conduct.

## Acknowledgements
AdvCalc was built using the following technologies and libraries:

React.js

Tailwind CSS

gh-pages

We would like to express our gratitude to the authors and contributors of these amazing tools that made this project possible.

## Contact
For any questions or inquiries about the AdvCalc project, please contact us at shashanksinghania120@gmail.com. We would love to hear from you!
