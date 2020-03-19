Launches chrome, kicks off lighthouse report, and stores in `lighthouse-reports`

### To Launch

node report.js --url `url`

### To compare

node report.js --from `filename` --to `filename`

This command prints out the metricFilters to the command line

### Viewing reports 

Copy file json into https://googlechrome.github.io/lighthouse/viewer/

### File Structure

lighthouse-reports is set to be created as a peer directory to report.js
Comments are made in the code as to how to change where the report directory is created, the path
to where the reports are stored. 