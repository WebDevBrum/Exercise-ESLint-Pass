# Exercise-ESLint-Pass

Instructions
Your goal is to set up an NPM project which will lint and prettify the code in index.js.

You are being supplied the configuration files for EsLint and Prettier ./.prettierrc & ./.eslintrc. Run ls -a in terminal to see invisible files are there. You do not need to make any changes to them.

Configure the NPM project
Install the proper node modules.
prettier Note: you'll need to use Prettier version 1.19.1 because version 2+ is not compatible with the workspace Node version)
eslint
eslint-config-prettier to turn off ESLint reult that conflict with Prettier
eslint-plugin-prettier which runs Prettier as an ESLint rule
Write scripts that run eslint and prettier.
Run the scripts to find the errors in index.js
Fix the errors and run the scripts again until the code is clean.
Hints
To figure out what to use for the script, try adding "lint": "eslint" as a script and read the help feedback for eslint to see what is missing.

To edit the package.json file, right-click on the file and select Open With and select Editor.

If you aren't sure how to fix an error, run an internet search on it.
