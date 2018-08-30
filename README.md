# Taranis

Taranis is a tool developed by NCSC-NL to facilitate the process of monitoring 
and analysing news items and writing security advisories.

## License

Taranis is published under the EUPL 1.2. See the LICENCE file, included in
the distribution for more information.  You can also read it at
<https://spdx.org/licenses/EUPL-1.2.html>

## Downloads and documentation

Both documentation and downloads of Taranis can be found in its
public GitHub repository at <https://github.com/NCSC-NL/taranis3/wiki>

# Roadmap

Taranis has some things which can be improved. This fork aims to improve upon those things.

## Requirements

The following requirements where identified (in decreasing importance):

### Source to multiple categories
Description: Taranis should be able to add a source to multiple categories.
Explanation: Some sources, like security.nl, just sends news. Some news has to do with explois, some with data breaches, etc. You don't want to add the same source twice. So a source should have a one-to-many relation with the categories. This can be implemented in the sources menu. Just give the option to specify zero or more categories and give the option to filter results per category.

### Category based filters
Description: Taranis should be able to filter irelevant entries from a category.
Explanation: Sometimes the filter on the source is not good enough. In that case the category filter should not display it. 

### Automatic image generation
Description: Taranis should generate images for sources automatically.
Explanation: The image feature right now is inconvenient. I have to create 72x30 images for sources, which could easily be generated.

### RSS category filters
Description: Taranis should be able to filter RSS feeds based on categories.
Explanation: Some RSS feeds have set categories for entries. Not all categories might be relevant so it should be removed from the Taranis feed. Could in theory be implemented with a wordlist, but that is a bit uncovenient.

### Full export resources
Description: all recourse in Taranis should be easy to export, either in JSON or XML format.

# Activity

Soon I will be starting with the implementation of the things mentioned on the roadmap. In will also try to write some pieces about the sources to include and how to manage the sources.
