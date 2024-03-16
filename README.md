![](src/icon.png)
# web3 daily Chrome Extension
This is a A tool for sharing web3 airdrop events and giveaway information.


### Features
- Search web3 airdrop events and giveaways by keyword in title, description, or code
- View web3 airdrop event details including title, description, and code (if applicable)
- Copy code snippet to clipboard with a single click
- Add new web3 airdrop event with a title, description, and optional code snippet


### Install dependencies:
```bash
> npm install
```

Build the extension for development:
```bash
> npm run build:dev
```

This command below runs the Tailwind CSS tool on the file "./src/style.css" and generates an output file "./dist/style.css" with the processed styles that are used to style the look and feel of the extension application.
```bash
> npx tailwindcss -i ./src/style.css -o ./dist/style.css
```

### Running Tests
Tests for this project are written using Jest. To run the tests, use the following command:
```bash
> npm test
```


### To install the extension in Chrome, follow these steps:
1. Open the Extension Management page by navigating to chrome://extensions.
2. Enable Developer Mode by clicking the toggle switch next to "Developer mode".
3. Click the "Load unpacked" button and select the dist directory in the project.
4. The extension should now be installed and you should be able to search for articles and view the results in the extension popup.

After following these steps, you will be able to view the installed extension in Chrome, as shown in the image below.

![](assets/screenshots/chrome-extension-knowledge-base.png)


### Usage
- Click on the web3 daily icon in your browser
- Type a keyword in the search bar to search for task and event information
- Click on an task or event to view its details
- Click on the "Copy" button to copy code snippets to your clipboard

