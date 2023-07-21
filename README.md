
# Project Lyrics

Develop an elegant React.js Music Application.

Check out the complete project requirements [here](https://docs.google.com/document/d/13PeFwRlPEhMw_HPyrIrInvQuKaVWnpNmcv-y3NA208s/edit?usp=sharing)

# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue.
Please note we have a [code of conduct](CODE_OF_CONDUCT.md), please follow it in all your interactions with the project.


## System Requirements

To get started with development, you need to install few tools

1. git

   `git` version 2.13.1 or higher. Download [git](https://git-scm.com/downloads) if you don't have it already.

   To check your version of git, run:

   ```shell
    git --version
   ```

2. node

   `node` version 16.15.1 or higher. Download [node](https://nodejs.org/en/download/) if you don't have it already.

   To check your version of node, run:

   ```shell
    node --version
   ```

3. npm

   `npm` version 5.6.1 or higher. You will have it after you install node.

   To check your version of npm, run:

   ```shell
    npm --version
   ```

## Setup

To set up a development environment, please follow these steps:

1. Clone the repo

   ```shell
    git clone https://github.com/JavaScript-Mastery-PRO/project1_team4_repository.git
   ```

2. Change directory to the project directory

    ```shell
    cd project1_team4_repository
    ```

3. Install the dependencies

    ```shell
     npm install
    ```

    If you get an error, please check the console for more information.

    If you don't get an error, you are ready to start development.

4. Run the app

    ```shell
    npm run dev
    ```

    Project will be running in the browser.

    Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Issues

You've found a bug in the source code, a mistake in the documentation or maybe you'd like a new feature? You can help us by [submitting an issue on GitHub](https://github.com/orgs/JavaScript-Mastery-PRO/projects/8). Before you create an issue, make sure to search the issue archive -- your issue may have already been addressed!

Please try to create bug reports that are:

- _Reproducible._ Include steps to reproduce the problem.
- _Specific._ Include as much detail as possible: which version, what environment, etc.
- _Unique._ Do not duplicate existing opened issues.
- _Scoped to a Single Bug._ One bug per report.


## Pull Request

There are 2 main work flows when dealing with pull requests:

* Pull Request from a [forked repository](https://help.github.com/articles/fork-a-repo)
* Pull Request from a branch within a repository

Here we are going to focus on 2. Creating a Topical Branch:


1. First, we will need to create a branch from the latest commit on master. Make sure your repository is up to date first using

   ```bash
    git pull origin main
   ```

   *Note:* `git pull` does a `git fetch` followed by a `git merge` to update the local repo with the remote repo. For a more detailed explanation, see [this stackoverflow post](http://stackoverflow.com/questions/292357/whats-the-difference-between-git-pull-and-git-fetch).

2. To create a branch, use `git checkout -b <new-branch-name> [<base-branch-name>]`, where `base-branch-name` is optional and defaults to `main`.

   Use a standard convention for branch names. For example, `<your-name>-dev`. It will be easier to track your pull requests if you use this convention.

   I'm going to create a new branch called `jsm-dev` from the `main` branch and push it to github.

   ```bash
    git checkout -b jsm-dev main
    git push origin jsm-dev
   ```

3. To create a pull request, you must have changes committed to your new branch.

4. Go to [Pull Requests](https://github.com/JavaScript-Mastery-PRO/project1_team4_repository/pulls) and click on the `New Pull Request` button.

5. Select the `main` branch as the `base` branch and the `jsm-dev` branch as the `compare` branch.

6. Follow the template and fill in the proper information for the pull request.

7. Click on the `Submit` button.

8. You have successfully created a pull request. Now wait for mentor approval. Once approved, you can merge the pull request.

#
=======
# Lyriks
Welcome to Lyriks! A feature-rich music application inspired by Spotify. With its modern homepage, fully-fledged music player, powerful search functionality, interactive lyrics display, comprehensive song exploration features, popular music around you, worldwide top charts, and much more, this application offers a delightful user experience.

## Features

- Modern homepage: The application features a sleek and modern homepage design that welcomes users and provides easy navigation to different sections of the app.

- Fully-fledged music player: Enjoy seamless music playback with a fully-featured music player. Play, pause, skip, and control the volume with ease.

- Search functionality: Find your favorite songs, artists, or albums using the powerful search feature. Get instant results as you type, making it easy to discover new music.

- Lyrics display: Dive deeper into the music by displaying lyrics alongside the playback. Sing along with your favorite songs or explore the meaning behind the lyrics.

- Song exploration: Explore related songs, artists, and albums to discover new music that suits your taste. Expand your musical horizons with personalized recommendations.

- Popular music around you: Stay up-to-date with the latest music trends by accessing popular songs and playlists from your local area. Discover what people are listening to nearby.

- Worldwide top charts: Get insights into the most popular music worldwide. Browse the top charts to discover trending songs, albums, and artists from across the globe.

## Technologies Used

This project is built using the following technologies:

- React: A popular JavaScript library for building user interfaces. It enables the creation of reusable UI components and facilitates efficient rendering.

- Redux: A predictable state container for JavaScript apps. Redux helps manage the application state and ensures consistency throughout the app.

- RapidAPI: A platform that allows developers to access a wide range of APIs, including music-related APIs. RapidAPI provides the necessary data and functionality to power the Spotify clone.

- Tailwind CSS: A utility-first CSS framework that provides a set of pre-defined classes to style the application. Tailwind CSS helps create a responsive and visually appealing design with ease.

- Vite: A fast and efficient build tool for modern web applications. Vite offers a smooth development experience by leveraging native ES modules to deliver near-instantaneous hot module replacement (HMR) and build times.

## Getting Started

To get started with the Spotify Clone project, follow these steps:

1. Clone the repository: `git clone <repository-url>`
2. Install dependencies: `npm install`
3. Obtain necessary API keys: Sign up on RapidAPI and obtain the required API keys for accessing music-related APIs.
4. Configure API keys: Add your API keys to the appropriate configuration file.
5. Run the development server: `npm start`
6. Open the application in your web browser: `http://localhost:3000`

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for additional features, feel free to open an issue or submit a pull request. Please follow the existing code style and conventions.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code for personal and commercial purposes.

## Acknowledgements

- The Lyriks project was inspired by the popular music streaming application, Spotify. We appreciate the Spotify team for their innovative product, which served as a reference for this project.

- We would like to express our gratitude to the developers and maintainers of React, Redux, and RapidAPI for providing excellent tools and services that made this project possible.

## Contact

If you have any questions or feedback regarding the Lyriks project, please feel free to reach out to us on GitHub. We'd be happy to assist you!
