# Contributing

This is mostly automated.

## Make your own

1. Create an `index` repo
2. Visit the Repositories tab on your profile
3. Run this in the console, it will copy some markdown to jump start the repo:

  ```js
  copy($$('.source').map(repo => {
    const name = repo.querySelector('[itemprop^="name"]');
    const desc = repo.querySelector('[itemprop^="description"]');
    return `* [${name.innerText}](${name.href}) - ${desc ? desc.innerText : 'ENTER DESCRIPTION'}`
  }).join('\n'));
  ```

4. Create README.md file with the contents of your clipboard
5. Setup this [GitHub bot](https://github.com/bfred-it/index-github-bot) on [zeit/now](https://zeit.co/now) to automatically remind you to add new repos by creating new issues.
