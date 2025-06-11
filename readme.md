So lemme tell you that To push code to GitHub from VS Code again
Click the Source Control (Git icon) on the sidebar or press Ctrl+Shift+G.

You'll see all changes listed under Changes.

Click the + icon beside files or click + next to Changes to stage all.

Type a commit message in the textbox at the top.

Click the ✔ (checkmark) to commit.
Click the ... (three dots) > Push, or press Ctrl+Shift+P → type Git: Push → Enter.

💡 VS Code automatically pushes to the same GitHub repo/branch used before.

-----------------------------------------------------------------------------
❓If You Created a New Project:
You need to:

Initialize Git: Ctrl+Shift+P → Git: Initialize Repository.

Connect remote:

bash
Copy
Edit
git remote add origin https://github.com/your-username/your-repo.git
git branch -M main
git push -u origin main
Or use the GitHub extension in VS Code to Publish to GitHub.