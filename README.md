To add a new blog post:

Create a new file, e.g., xyz.md in the posts folder. 

The starting (front matter) of the markdown file looks like 
```
---
title: <Title>
date: YYYY-MM-DD
section: <musings><diversions><obligations>
---

<content>
```
Run the script generate-posts-list.js using `node generate-posts-list.js`

Push the changes to github. 

generate-posts-list.js script fetches the metadata from each md file in the posts folder and uses it to categorize and create various json files containing in appropriate category in reverse chronology