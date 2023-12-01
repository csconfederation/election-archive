## Running the site locally
- Install [hugo](https://gohugo.io/installation/)
- Run the dev server with `hugo server`

## Setting up a new season
- Run `hugo new content posts/season[number]/admin.md`
- Copy the exported html files to `static/season[number]/admin`
- Copy the contents of an old `admin.md` to the new `admin.md` and make the nessesary updates

## Adding additional elections
- Copy the expored html files to `static/season[number]/[election type]`
- Copy an existing md file from a previous season to `posts/season[number]` and make the nessessary updates