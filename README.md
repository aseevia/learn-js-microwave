## Introduction
Microwave oven implementation in vanilla JavaScript. Fun yet challenging learning project aimed at junior and wannabe frontend developers, allows to hone foundational skills and leaves room for expressing creativity. Can be used as a "take home" frontend interview assignment.

## 🚀 Quick start

1.  **Clone the repo**

    Clone the repo if you haven't done that already.

    ```shell
    git clone git@github.com:aseevia/learn-js-microwave.git
    ```

2.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```shell
    cd learn-js-microwave/
    npm install
    npm start
    ```

3.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8080`!
    Open the `learn-js-microwave` directory in your code editor of choice and editing files under the `public/` folder until you are happy with the result.


## Materials & prerequisites
- Figma design file containing sketch of the microwave can be found [here](https://www.figma.com/file/SBZOZRjSux08YRCynShX8r/Microwave?type=design&mode=design&t=8Vo6iGPifDUJc4Uf-1).
- Consider playing through the figma user [flow](https://www.figma.com/proto/SBZOZRjSux08YRCynShX8r/Microwave?type=design&node-id=49-7&t=pUvdPLl3Kjeo5jab-0&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=49%3A7) to see an example of how the final implementation may look and function.
- MP3 files can be found under the [sounds](/public/sounds/) folder.
- [index.html](/public/index.html), [index.js](/public/index.js) and [style.css](/public/style.css) files are pre-wired for your convenience.

## Rules
- Use only plain HTML and CSS, no pre/post processors or libraries
- Avoid using images, all the shapes should be created with HTML tags and CSS styling only.
- CSS should be compliant with [BEM methodology](https://en.bem.info/methodology/)
- Code required for the microwave to function should be plain JavaScript ready to be executed in any modern browser, no libraries, frameworks or transpilers are allowed.
- **npm** usage is only allowed for developer tools like the **http-server**, **testing libraries** and **gh-pages** cli.

## Implementation requirements
- Users should be able to open and close the door and place food inside the device.
- Uses should be able to start the cooking process.
- Cooking process should start the timer for 30 seconds by default, process stops when the timer reaches 0.
- Users should be able to extend cooking timer in 30 secord increments at any time during the cooking process.
- Starting of the cooking process is only possible when the device door is closed.
- Users should be able to clearly observe what is happening inside the device during the cooking process, including steam rising above the food (light is on).
- Users should be able to stop cooking process at any time.
- Users should be able to open the device door at any time, this should also stop the cooking process.
- Opening of the door, starting/stopping of the cooking process and the process itself are accompanied by corresponding sounds from the [sounds](/public/sounds/) folder.

## Nice-to-haves 
- Unit tests coverage
- Bite-sized commits and meaningful messages.

## Delivering the result
1. When you are done with the implementation, star this repo 😊, deploy your solution to [GitHub pages](https://docs.github.com/en/pages) and share the link with your interviewer/mentor or just your friends 👍
2. Stand in front of the mirror, take a power-pose and congratulate yourself for being such a great developer! 🎉🎉🎉