# webpack-react-test
Simple test to launch react app with web pack and have the opportunity to customize builds

###
First Steps, 
- Initialize NPM ny running
 ` npm init `
- Install the following dependencies (Production and Development)
    - react and react-dom
        ` npm i react react-dom`
    - These are the dev dependencies needed
        - babel/core
        - babel/preset-env
        - babel/preset-react
        - babel-loader => will load all react code to browser readable format
        - css-loader and style-loader => help load cdd to html doc and style loader will create the stle tag in our html doc
        - file-loader => will be used to load our html file to our output
        - sass and sass-loader => helps convert saas to css
        - webpack and webpack-cli => helps us bundle our code for the browser
- Create a babelrc file at root of application and confiugure as shown
- Create a webpack.config,js file and setup as shown
