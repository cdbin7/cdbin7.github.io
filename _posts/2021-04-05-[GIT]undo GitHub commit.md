---
layout: post
title: _GIT_ undo pushed commit on GitHub
subtitle: "I want to remove some commits and go back to certain one"
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [books, test]
---

After you commit and push to GitHub, what should you do if you want to undo these and push it again?

Let's say you want to go back to 'First commit'

- commit C
- commit B
- commit A
- First commit

```git reset --hard HEAD~3 ```
```git push origin master``` -> you will get an error [rejected]
```git push -f origin master```

Remember this seems the best way only if you don't share your repository with anyone. So If you are the only one who use this branch, this is a great way to fix your issue.
