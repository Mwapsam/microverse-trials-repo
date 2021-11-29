This is the website for the Biography of Thomas Edison

Built With

    Major languages
    HTML
    CSS

Getting Started

This is an example of how you may give instructions on setting up your project locally. Modify this file to match your project, remove sections that don't apply. For example: delete the testing section if the currect project doesn't require testing.

To get a local copy up and running follow these simple example steps.
Prerequisites

    HTML
    CSS
    Linters

Setup

git clone https://github.com/Mwapsam/portifolio.git

cd portfolio
Install

npm init -y

# LINTER SETUP

# .gitignore
node_modules/

# Webhint
npm install --save-dev hint@6.x
npx hint .

# Stylelint

npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x

npx stylelint "**/*.{css,scss}"