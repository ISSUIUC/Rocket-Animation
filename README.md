# Rocket-Animation

To build:

Go to ./new-rocket-animation/
Run npm install
Run browserify src/main.js -o src/index.js
Note: Make all js changes in main.js; browserify is for bundling for deployment

To deploy:

Go to ./new-rocket-animation/
Run browserify src/main.js -o src/index.js
Run npm start
Navigate to the localhost site that shows up
Do NOT use live preview - it will complain that "require()" is not defined.

Changes will be live, but for any changes you make to main.js, you must rebundle with browserify, or else the changes won't be reflected.
