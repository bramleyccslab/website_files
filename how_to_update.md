#How to update

1. Install hugo: [here](https://gohugo.io/getting-started/installing/)

2. Run a development server in website_files: `hugo server`

3. Check it in browser: `http://localhost:1313/`

4. `ctrl+4` to stop

5. To rebuild: clear `/public` (but leave `/experiments`), run `hugo` in `website_files` to repopulate public

6. `git add`, `git commit -m description`, `git push origin master` in `\website_files` to update the build files repo

7. `git add`, `git commit -m description`, `git push origin master` in `\public` to update the actual website repo

