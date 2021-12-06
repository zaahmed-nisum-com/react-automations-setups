# Automate your React app to check code quality check the eslint errors and forcefully run the prettier

 ### Step 1: npx create-react-app "app name"
 ### Step 2: npm install --dev eslint-config-prettier  
 ### Step 3: npm install --dev --exact prettier   
 ### Step 4: npm install --dev eslint-plugin-prettier
 ### Step 5: npm install eslint --save-dev    
 ### Step 6: npm npx eslint --init   
 ##### This command will create file .eslintrc with some basic confiduration and you can add some rules for you code fromating and quality in this file.
 ##### After this check the packge.json file we have configure husky and lint-staged to run few commands for us on git commit to format/prettier and eslint in our code.
 ### Step 7: npm install husky --save-dev  
 ### Step 8: npx mrm@2 lint-staged
 #### This command will create a folder with .husky name and a file with pre-commit file having command "npx lint-staged". So when you commit your code on git it will run the command and check if their is any code error it will not commit the code until all the errors resolve.
     
 
 
