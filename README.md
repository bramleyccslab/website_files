# How to update

## Requirement

Install [hugo](https://gohugo.io/getting-started/installing/).


## Update the website

1. Always do a `git pull` before making changes, to make sure you don't accidentally ignore others' edits

2. Run a development server in website_files: `hugo server`

3. Make changes

4. Check it in browser: `http://localhost:1313/`

5. `ctrl+c` to stop

6. `git add`, `git commit -m description`, `git push origin master` to update this repo (so that others can sync your changes)

7. To rebuild: clear `/public`, run `hugo` in `website_files` to repopulate public

8. Use [cyberduck](https://www.cyber-duck.co.uk/) to connect to the server Host: `chost4.is.ed.ac.uk` User: `wwwbramleylabppl` Password: `******************ugJi`, SFTP - SSH connection.

9. Replace everything in `\www` on the server with everything in `\public` on the local copy (exlcuding any experiment folder that may be maintained separately)
