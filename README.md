# Team-Profile-Generator

<h1 align="center">Team Profile Generator</h1>

  <p align="center">
    <img src="https://img.shields.io/github/repo-size/MichaelPappas2662/Team-Profile-Generator" />
    <img src="https://img.shields.io/github/languages/top/MichaelPappas2662/Team-Profile-Generator"  />
    <img src="https://img.shields.io/github/issues/MichaelPappas2662/Team-Profile-Generator" />
    <img src="https://img.shields.io/github/last-commit/MichaelPappas2662/Team-Profile-Generator" >
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/-node.js-green" />
    <img src="https://img.shields.io/badge/-inquirer-red" >
    <img src="https://img.shields.io/badge/-jest-blue" >
    <img src="https://img.shields.io/badge/-screencastify-lightgrey" />
    <img src="https://img.shields.io/badge/-json-orange" />
</p>

# Table of Contents

* [Installation](#-Installation)
* [user Story](#-User-Story)
* [Tests](#-Tests)
* [Questions](#-Contact-Information)

## Installation

run node index.js at the terminal

## User Story

```md
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated
```

## Test

![](./assets/test.png)

## Video

[video](https://drive.google.com/file/d/1o7alYNwhKjvyH437NW_lRjwRiibLqFt_/view)
