# SearchByTap
An AI-Powered Chrome Extension to Enhance Your Browsing Experience with Intelligent Definitions.


### To create the new nextjs project

`npx create-next-app@latest`

### To build the nextjs app
**In package.json in the Scripts section write this build command:** This command can be used for Unix and Linux OS.

`"build": "next build && mv out/_next out/next && cp -r ./extension/* ./out",` 

 The `npm run build` command in a Next.js project creates an optimized production build by compiling and minifying the code and generating static assets for deployment.
 ## Features
1. Provides immediate definitions of any selected word with a single tap or click, eliminating the need for manual searches.
2. Retrieves definitions and information from a variety of sources including:Wikipedia,Chatgpt,Youtube,etc.
3. Provides not just the definition, but also additional contextual information such as usage examples, synonyms, and related concepts.
4. Features a user-friendly interface that integrates seamlessly with different websites and adjusts to different screen sizes for an optimal viewing experience.
5. Ensures quick response times and reliable performance by optimizing API calls and using efficient coding practices.

## Installation Instructions

Google Chrome / Microsoft Edge (Custom sites supported)

1. Download this repo as a ZIP file from GitHub.
2. Unzip the file and you should have a folder named SearchByTap-extension.
3. In Chrome/Edge go to the extensions page (chrome://extensions or edge://extensions).
4. Enable Developer Mode.
5. Drag the SearchByTap-extension folder anywhere on the page to import it (do not delete the folder afterwards).


 Mozilla Firefox (Custom sites not supported)
1. Download and install the latest version


## Notes

1. Every time you open Chrome it may warn you about running extensions in developer mode, just click ✕ to keep the extension enabled.
2. You will be logged out for any site you have checked.
3. This extension works best alongside the adblocker uBlock Origin.
4. The Firefox version supports automatic updates.
    
## Troubleshooting
1. This extension works best alongside uBlock Origin for Google Chrome or for Mozilla Firefox.
2. If a site doesn't work, try turning off uBlock and refreshing.
3. Try clearing cookies.
4. Make sure you're running the latest version of SearchByTap.
5. If a site is having problems try unchecking "*General SearchByTap*" in Options.
6. If none of these work, you can submit an issue here.
## Contributing - Pull Requests
PRs are welcome.

1. If making a PR to add a new site, confirm your changes actually bypass the paywall.
2. At a minimum these files need to be updated: README.md, components.json, next.config.mjs, and possibly tailwind.config.ts, and/or postcss.config.mjs.
3. Follow existing code-style and use camelCase.
4. Use JavaScript Semi-Standard Style linter. Don't need to follow it exactly.

## Show your support
1. Follow me on Twitter @mohitjoping for updates.
2. I do not ask for donations, all I ask is that you star this repo.
 

 
