These exercises are basic but can help someone who is beginning to learn or has forgotten Git and GitHub.

I created two folders, ignore_all and not_ignoring. I’m not going to track the first folder, but I will keep track of the second folder.

I created four files in the root directory. I’m tracking two files (text1.txt and text2.txt) and not tracking two others (.env and .gitignore).

After creating a repository and pushing it to GitHub, I noticed that my .env file appeared on GitHub, which isn’t normal. I can’t give access to my database because it’s not safe for my application.

I untracked the .env file, created another commit, but saw the same issue. Oops! I forgot to fully untrack the file in Git. After doing that, it worked.
