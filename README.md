# Sourcify ABI Transformer for Glaciers

This repository contains a script to source and transform ABIs from Sourcify into the specific format required by Glaciers.

## Overview

Glaciers require an ABI database to decode raw Ethereum logs effectively. This script helps streamline the process by:

 - Download and extract verified ABIs from Sourcify.
 - Filter and format them for compatibility with Glaciers.

## Instructions

To use this script, you need to install the Python package for [Glaciars](https://github.com/yulesa/glaciers) and [Polars](https://docs.pola.rs/)

```pip install glaciers polars```

## Usage

- Download the Sourcify repository. Follow the instructions in [Sourcify's documentation](https://docs.sourcify.dev/docs/repository/sourcify-database/#download). You can edit the manifest to download only the necessary files.
- Once downloaded, move each file to dedicated folders and execute the notebook to extract and format the ABIs for Glaciers:

## Open-Source

Sourcify is a public good and non-profit project. It's fully open and transparent. It started under the Ethereum Foundation and now is part of the Argot Collective.

This project wouldn't be possible without it, and we are very grateful for this public good.

## Contribution

Contributions and improvements are welcome! Feel free to submit an issue or pull request.
