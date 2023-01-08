# stackoverflow-code-language-switcher

Adds a dropdown to code blocks in StackOverflow to switch the code language. Powered by GPT-3 AI.

![Screenshot 1](/screenshot.png)

![Demo](/demo.gif)

## Requirements

1. Install [Violentmonkey](https://violentmonkey.github.io/), [Tampermonkey](https://www.tampermonkey.net/), or [Greasemonkey](https://www.greasespot.net/).

2. [OpenAI API Key](https://openai.com/)

## Installation

1. Install from GreasyFork: https://greasyfork.org/en/scripts/457875-stackoverflow-code-language-switcher or manually install the `userscript.js`.

2. Once installed, open the script editor/settings, and under "values", set the `openai_key` to your OpenAI API key.

## Usage

1. Go to a StackOverflow question with code blocks.

2. Click on the language dropdown to switch the code language.

The lanuage list can be customized by editing the `supported_languages` array in the script "values" config.
