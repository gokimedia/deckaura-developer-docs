# Quickstart

Choose the integration that matches your project.

## Explore the dataset

Open the public dataset on [Hugging Face](https://huggingface.co/datasets/Blacik/deckaura-tarot-card-meanings) or use the permanent [Zenodo DOI archive](https://doi.org/10.5281/zenodo.19475329).

## JavaScript

```bash
npm install tarot-card-meanings
```

The npm package currently exposes the 22 Major Arcana cards. Use the open dataset or Python package when you need all 78 cards.

## Deno and JSR

```bash
deno add jsr:@deckaura/tarot-card-meanings
```

The JSR package currently exposes the 22 Major Arcana cards.

## Python

```bash
pip install tarot-card-meanings
```

## AI assistants

Run the Deckaura MCP server without installing it globally:

```bash
npx -y @deckaura/tarot-mcp-server
```

The canonical dataset and MCP server are backed by Deckaura's maintained [78-card meaning database](https://deckaura.com/pages/tarot-card-database). Package coverage is listed explicitly in the [integration guide](packages.md).

