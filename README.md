# SB App Studio - Developer Profile

Welcome to the **SB App Studio** Developer Profile website! This is a highly aesthetic, premium, and fully responsive static website designed to showcase your organization, display your public contact details, and feature your applications like **Astronumy**.

## Features
- **Premium Dark Mode Design**: Utilizes a deep purple and blue aesthetic with glassmorphism (frosted glass) effects.
- **Fully Interactive**: Includes an interactive, mouse-reactive particle background and 3D card tilt effects for a dynamic user experience.
- **Fast & Lightweight**: Built purely with HTML, Vanilla CSS, and JavaScript. No build tools or heavy frameworks required, ensuring instant load times and perfect SEO.
- **App Showcase**: Contains a detailed, interactive modal popup showcasing the Astronumy app.

## Project Structure
- `index.html`: The main markup file containing the structure of the website.
- `style.css`: All styling, animations, and responsive design rules.
- `script.js`: Handles smooth scrolling, scroll animations, the Astronumy info modal, and the interactive particle background.
- `sb-logo-transparent.png`: The main studio logo with a transparent background.
- `astronumy-icon.png`: The application icon for Astronumy.

## Local Development
Because this is a pure static website, you do not need to install any node modules or run complex build commands.

To view the website locally:
1. Open the project folder.
2. Double-click on `index.html` to open it in your default web browser.

*Note: For the absolute best experience (especially for certain JavaScript animations), it is recommended to run a local server (e.g., using `python3 -m http.server 8080` or the VS Code Live Server extension).*

## Hosting & Deployment

This website is ready to be hosted immediately. Since you've opted not to use GitHub pages, here are two of the best, completely free alternatives for hosting static websites: **Vercel** and **Netlify**.

### Option 1: Deploying with Vercel (Recommended)
Vercel is blazing fast and incredibly easy to use.

**Method A: Drag and Drop**
1. Create a free account at [Vercel](https://vercel.com/signup).
2. Go to your dashboard and click **Add New Project**.
3. Skip the Git import section. Instead, look for the **Drag and drop** area.
4. Drag your entire `sb-app-studio` folder into this area.
5. Vercel will instantly upload and deploy your website, providing you with a live URL!

**Method B: Vercel CLI**
1. Install the CLI via terminal: `npm i -g vercel`
2. Run `vercel` inside the `sb-app-studio` directory.
3. Follow the prompts (use default settings) and it will upload and give you a production URL.

### Option 2: Deploying with Netlify
Netlify is another outstanding platform for hosting static files for free.

**Method A: Netlify Drop**
1. Go to [Netlify Drop](https://app.netlify.com/drop).
2. Drag and drop the `sb-app-studio` folder directly onto the page.
3. Your site will be live in seconds. You can then create an account to claim the site and change the URL name to something like `sb-app-studio.netlify.app`.

---

*Designed and Built by Antigravity (Google DeepMind).*
