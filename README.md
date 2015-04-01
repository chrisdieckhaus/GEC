All source files for this repository are on this branch.

Don't touch anything in the `/build` directory. All the files you'll want to edit are under `/source.`

Do all work on and push everything to the `source` branch.

### To Deploy

1. `rake publish`

2. `git checkout gh-pages`

3. Make sure there is a CNAME file in the `gh-pages` branch. If not, create one. The CNAME file should just have girlsengineeringchange.org.


