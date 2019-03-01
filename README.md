# CSS-JS Code Quality Validator
CSS/SCSS/LESS/JavaScript validation rule for easy code quality check.  

#prerequisite
Make sure node js install in the system

#Set up guideline
1. Download the repo
2. Run npm install
3. Place CSS/SCSS/LESS/JavaScript
4. Run below command based of type of file to validate

For LESS- stylelint "**/*.less" --config .style.json > style_report.txt

For CSS- stylelint "**/*.css" --config .style.json > style_report.txt

For SCSS- stylelint "**/*.scss" --config .style.json > style_report.txt

For Script- eslint script.js > script_report.txt