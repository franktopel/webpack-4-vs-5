# webpack-4-vs-5
Small test repository for quick Javascript feature support testing in webpack 4 and 5

# Instructions

0. Open your terminal of choice and navigate to your workspace folder.
1. `git clone https://github.com/franktopel/webpack-4-vs-5`
2. `cd webpack-4-vs-5`
3. `npm install`

## Test your feature
You can now add features you want to test in `src/features/{{you-name-it}}.js`, one file per feature. 

Once you added a feature, make sure you import your file in `src/entry.js`. Comment the lines for the features you don't want tested.
 
To test if webpack 4 (through webpack-stream via gulp) supports your feature: `npm run gulp-webpack-4`.  
To test if webpack 5 supports your feature: `npm run webpack-5`.
