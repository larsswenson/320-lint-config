Configuring ESLint in Node.js

After initially installing ESLint, I had to start over because I'd named my directory the overly obvious "eslint", which the actual ESLint installer refused. I had to delete the directory and rename a new one. I'm not sure it was correctly installed because my npm version may be obsolete but it said it was successful. However, there were no rules in the eslintrc.cjs file-- NO RULES! ;)~ I added the ones regarding quotes and semicolons. Before I linted my very simple JavaScript file, I created some problems by removing semicolons and qoutes so I could test the behavior of ESLint. The screenshot shows the problems it flagged (and didn't) based on my rules. From my limited experience, my takeaway is that ESLint is an efficient and convenient way to customize code constraints, whether through errors, warnings, or neither, depending on one's preferences. 


