# accessibility challenges

Welcome to the introduction page of accessibility challenges for coders! The purpose of this project is to offer a platfor to reherse making accessibility improving changes to a web page. So the sad side of the story is that a large part of people would not be able to use this website, because accessibility has not been taken into account in its development. Do you know what should be done to improve accessibility of this page?

This project has been made with Vue 3 and TypeScript with script setup. You can download the project to your own computer and run it locally. Introductions how to get started are placed in the next chapter.




## Get started with the project

### Prerequisites

Before you can run this project, you need to have the following tools installed on your computer:

-   **Node.js and npm:** Node.js is a JavaScript runtime that is required for running a Vue.js project. npm (Node Package Manager) is included with Node.js and is used for managing and installing project dependencies. You can download Node.js and npm from [here](https://nodejs.org).

-   **A Code Editor:** For writing code, you'll need a code editor. [Visual Studio Code](https://code.visualstudio.com/) is a great choice for JavaScript and Vue.js development.

    -   **Quality of life extensions:** <b style="color:red">Volar</b> is the recommended extension for vue3 + typescript projects and will save you from some grey hairs (Vetur doesn't work well with vue3).
        <b style="color:red">Prettier, ESLint</b> or some similar extensions that can be set to format code on save.

-   **Git:** Git is a version control system that allows you to track your code changes and work collaboratively with other developers. Download it from [here](https://git-scm.com/downloads).

### Cloning and Running the Project

1. **Clone the project**: Navigate to the directory where you want to clone the project in your terminal/command prompt. Run the following command to clone the project from GitHub:

    ```bash
    git clone https://github.com/laladdin/accessibility-challenges.git
    ```

2. **Navigate to the project directory**: Use the command `cd accessibility-challenges`.

3. **Install the project dependencies**: In the project directory, run the command `npm install` to install all necessary dependencies.

4. **Open project in Visual Studio Code**: In the project directory, run the command `code .` to install all necessary dependencies.

5. **Start the development server**: Run the command `npm run dev` to start a local development server. Once the server is running, you'll be able to open your project in a web browser.

### Viewing the Project

Open a web browser and navigate to localhost:8080 (or the address specified in your terminal/command prompt after running npm run dev). You should now see your Vue.js project running.




## Get Started with screen reader NVDA

Here are the steps to download and install NVDA (NonVisual Desktop Access), a popular open-source screen reader:

1. **Download NVDA:** Visit the [NVDA website](https://www.nvaccess.org) and download the latest version of NVDA. As of my knowledge cutoff in September 2021, NVDA is only available for Windows operating system.

2. **Install NVDA:** Open the downloaded file to begin the installation process. The installer will guide you through several steps, including choosing a language and accepting the license agreement. You'll also have options for creating desktop and Start menu shortcuts.

3. **Choose Install Options:** There are options to use NVDA on the Windows logon screen (recommended for users who require screen reader assistance during login) and for automatically starting NVDA after you log on to your computer.

4. **Complete the Installation:** After choosing your options, proceed to complete the installation. Once finished, you'll have the option to start NVDA immediately.

5. **Learn NVDA Commands:** After NVDA is installed and running, you'll interact with your computer mostly via keyboard commands. A full list of commands can be accessed in the NVDA User Guide.

6. **Access NVDA User Guide:** The User Guide is a comprehensive resource for learning how to use NVDA. You can access it by pressing the NVDA key (usually the INSERT key) + N, then selecting "Help" and "User Guide".




## NVDA Shortcut Keys

Here are some of the most commonly used NVDA shortcut keys:

### Navigating Text:
- **Arrows:** Navigate by character/line.
- **Control + Arrows:** Navigate by word/paragraph.
- **Home/End:** Start/end of line.
- **Control + Home/End:** Start/end of document.

### NVDA Key:
The NVDA key is used in combination with other keys to execute commands. By default, it can be either INSERT or CAPS LOCK.

### NVDA Commands:
- **NVDA + Space:** Toggle focus and browse modes.
- **NVDA + S:** Toggle speech mode (speech off, beep for speech, or full speech).
- **NVDA + Q:** Exit NVDA.
- **NVDA + N:** Open NVDA menu.

### Web Browsing:
- **H:** Heading.
- **B:** Button.
- **E:** Edit field.
- **F:** Form field.
- **D:** Landmark.
- **M:** Frame.
- **N:** Move to the next block of text with the same formatting.
- **R:** Read from the current position.
- **K:** Link.
- **L:** List.
- **I:** List item.
- **T:** Table.
- **S:** Blockquote.
- **W:** Check spelling errors in document.

### Read Current Item:
- **NVDA + Up Arrow:** Read the current line.
- **NVDA + Down Arrow:** Spell the current line.
- **NVDA + Left Arrow:** Read the current word.
- **NVDA + Right Arrow:** Spell the current word.
- **NVDA + Numpad 5:** Read current character.
- **NVDA + Numpad 5 (twice quickly):** Spell current word.
- **NVDA + Numpad 5 (thrice quickly):** Spell current word phonetically.




## Other Useful Links

- [WCAG 2.1 Guidelines](https://www.w3.org/TR/WCAG21/)
- [Wave Accessibility Tool (Browser Extension)](https://wave.webaim.org/)

