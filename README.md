![deploy](https://github.com/mellypop/curse-of-strahd/.github/workflows/deploy.yml/badge.svg)

# Curse of Strahd Notes

This repository is for all of my notes related to a Curse of Strahd campaign that
I am a player in. I take my notes in [Obsidian](https://obsidian.md), and this
repository is mostly handled by the [Obsidian Github Publisher plugin](https://github.com/ObsidianPublisher/obsidian-github-publisher),
so check the documentation for that plugin if you want to create your own.

## The Notes

The easiest way to view the notes is to visit the gh-pages site associated with
this repository [here](https://mellypop.github.io/curse-of-strahd).

## Contributing

As this is a repository for a single instance of a campaign, I am not expecting
much, if any, contribution, but issues are welcome.

### Creating a local copy

To run the blog locally, you need to install the requirements and run `mkdocs serve`.

`cd publish_blog pip install -r requirements.txt mkdocs serve`

A tip: You can use a [conda](https://docs.conda.io/en/latest/) environment here (or a venv, but I prefer conda). Just use this command:

```bash
conda create -n Publisher python=3.11
conda activate Publisher
```

Run this command just before running `pip install`.
