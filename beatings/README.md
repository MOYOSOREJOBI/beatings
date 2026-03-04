# BEATINGS

Static HTML beat maker.

The app itself is in `dist/index.html`. A root `index.html` now redirects to `dist/`, which makes this repo easy to publish on static hosts.

## Fastest way to get a public link

Use Netlify Drop:

1. Go to `https://app.netlify.com/drop`
2. Drag the `dist` folder from this project into the page
3. Netlify will upload it and immediately give you a public URL

## GitHub Pages option

1. Create a new GitHub repo
2. Upload this whole project
3. In the GitHub repo, open `Settings > Pages`
4. Under `Build and deployment`, choose `Deploy from a branch`
5. Select your main branch and the `/ (root)` folder
6. Save, then wait a minute for GitHub to publish it

Your public URL will look like:

`https://your-username.github.io/your-repo-name/`

Because the root `index.html` redirects to `dist/`, the app will open correctly from that link.

## Original source

Original CodePen URL:
`https://codepen.io/Moyosore-Ogunjobi/pen/WbxmdYJ`
