# How to update

1. Install hugo: [here](https://gohugo.io/getting-started/installing/)

2. Run a development server in website_files: `hugo server`

3. Check it in browser: `http://localhost:1313/`

4. `ctrl+4` to stop

5. To rebuild: clear `/public`, run `hugo` in `website_files` to repopulate public

6. `git add`, `git commit -m description`, `git push origin master` in `\public` to update the actual website repo

7. Use [cyberduck](https://www.cyber-duck.co.uk/) to connect to the server Host: `chost4.is.ed.ac.uk` User: `wwwbramleylabppl` Password: `******************ugJi`, SFTP - SSH connection.

8. Replace everything in `\www` on the server with everything in `\public` on the local copy (exlcuding any experiment folder that may be maintained separately)