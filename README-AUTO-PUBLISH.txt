GitHub-only automatic publish setup

Upload these files to the root of your repo:
- index.html
- admin.html
- league-data.json

Admin URL:
https://hava999.github.io/cricket26-league/admin.html

Public viewer URL:
https://hava999.github.io/cricket26-league/

How auto-sync works:
1. Create a GitHub fine-grained Personal Access Token.
2. Give it access only to repo: hava999/cricket26-league.
3. Permissions: Contents = Read and Write.
4. Open admin.html.
5. Paste token into the GitHub Auto-Publish box and click "Save Token & Publish".
6. Paste match data in the admin match editor and click Save Match.
7. Admin automatically commits league-data.json to GitHub.
8. Public index.html reads league-data.json every 30 seconds.

Important:
- The token is stored only in your browser localStorage.
- Do not share admin.html token with friends.
- Friends only use index.html.
