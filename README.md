# How to update

1. Install [hugo](https://gohugo.io/getting-started/installing/) -
n.b. the current project works with hugo version 0.55.1, not compatibale with the latest version of hugo.

   Mac users with homebrew can use the command below.

   ```
   brew install https://raw.githubusercontent.com/Homebrew/homebrew-core/817ed69007a47e178e0033ae62c054b7bea2ed86/Formula/hugo.rb
   ```

2. Run a development server in website_files: `hugo server`

3. Check it in browser: `http://localhost:1313/`

4. `ctrl+c` to stop

5. To rebuild: clear `/public`, run `hugo` in `website_files` to repopulate public

6. `git add`, `git commit -m description`, `git push origin master` in `\public` to update the actual website repo

7. Use [cyberduck](https://www.cyber-duck.co.uk/) to connect to the server Host: `chost4.is.ed.ac.uk` User: `wwwbramleylabppl` Password: `******************ugJi`, SFTP - SSH connection.

8. Replace everything in `\www` on the server with everything in `\public` on the local copy (exlcuding any experiment folder that may be maintained separately)
