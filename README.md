# TPPM Website

Welcome to the TPPM site. This is going to serve as the primary website for TPPM going forward, created by the community itself.

### Installation

Setting up the dev environment is easy. Clone the Repo with git and run `npm install`. You must have Node installed on your machine.

### Setting up Environments

When you are ready to set up the server (running on port 3000), run `npm run dev` as any changes done on a file will _NOT_ require a restart of the app in the terminal. When you are ready for production, run `npm run production`. These are the two methods of running the app.

For running the front-end, we want to go into the tppm/ folder and run `npm start` for starting up the dev server. Front-end is going to run independently from the rest of the API but it is going to be communicating with it, hence why both are run separately.
