# seekr-gui

A gui for seekr

## Overview

seekr-gui is a gui for seekr. It is a command line tool that takes a list of words or phrases in a file, and traverses
pages in search of those terms in the DOM. There is a feature that will expand each word in the list to its additions,
subtractions, substitutions, and transpositions, and search for those as well. The tool will output a list of pages that
contain the terms.

## Requirements

seekr-gui requires:
- [node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [typescript](https://www.typescriptlang.org/)
- [yarn](https://yarnpkg.com/)
- [seekr](https://github.com/Internet-Computer-Tools/seekr)

## Installation

From the root of the project, run:

```bash
yarn
```

## Usage

Create a file with a list of words or phrases to search for. For example, `dictionary.txt`:

```text
cabbage
lettuce
```

Create a file with a list of domains that are crawlable. For example, `interesting_dmains.txt`:

```text
google.com
wikipedia.org
```

Run the gui:

```bash
npm run start
```