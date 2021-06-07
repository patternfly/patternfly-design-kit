# PatternFly Design Kit
The PatternFly Design Kit is a collection of [Sketch](https://www.sketchapp.com) assets that make it easy for designers to create high-fidelity design mockups that accurately represent [PatternFly](http://patternfly.org) components and layouts. It includes:

* A Sketch symbol library that includes components, icons, color palettes, and other PatternFly elements. Hosted on Sketch Cloud [here](https://www.sketch.com/s/2cf1063b-5283-4e0b-b8a6-cbb1ac07e29e).
* A template file that provides several starter layouts that will make it easier to construct common PatternFly screens. Hosted on Sketch Cloud [here](https://www.sketch.com/s/729c2eee-e8b6-4fcd-8a79-f6faa8c30f89).

## Updating the kit
Sketch will automatically receive library updates in the top, right corner of an open Sketch file. You'll want to update the PatternFly library **and** update the symbols within your file (two separate notifications). You'll have to update **all** files that are using PatternFly symbols - it is not a one and done process, unfortunately.

To update you PatternFly Template file, open the updated template from your local repo and select **File > Save as Template...** This will replace the current template with the updated version and make the latest layouts available using the **New from Template...** feature.

Please check out our [announcements](https://github.com/patternfly/patternfly-design-kit/blob/master/Announcements.md) for specific design kit release updates!

## Filing bugs
If something isn't working as expected with the library or template file, please file an issue in this repo and label it with "bug". We should be able to fix it within a couple days! 

## Release notes
To check out the latest design kit release notes, go [here](https://github.com/patternfly/patternfly-design-kit/blob/master/PatternFly%20release%20notes.md).

Please check out our [announcements](https://github.com/patternfly/patternfly-design-kit/blob/master/Announcements.md) for specific design kit release updates!

## Contributing to the PatternFly Design Kit
We welcome contributions from our community of PatternFly designers. Please contact Marie Doruskova (@doruskova) on the #patternfly-design-kit channel within the [patternfly.slack.com Slack workspace](https://patternfly.slack.com).
### Contributing a new or edited symbol
Follow these steps:
1. Download the library file from [here](https://www.sketch.com/s/2cf1063b-5283-4e0b-b8a6-cbb1ac07e29e).
2. Create new symbols or edit symbols using the styles and elements from "Document".
**Be sure you take them from "Document" rather than "PatternFly"**
3. When naming a new symbol, follow the naming mechanism within that same category (e.g., Forms / 2. Text Box / Success).
4. Make it clear which page in the file you edited and which symbols on the page you added/edited by adding a ⭐️ or some other mark to call them out.
5. Add the labels **"Pre-release"** to symbols that haven't been implemented yet or **"Core-only"** to symbols that are available only in HTML. This info is usually added to the description of the issue.
6. Zip your file and attach it to the GitHub issue you were assigned to. Add a list of the symbols you added/edited and, finally, tag @doruskova in your comment.
### Contributing a new or edited template
Follow these steps:
1. Download the template file hosted on Sketch Cloud from [here](https://www.sketch.com/s/729c2eee-e8b6-4fcd-8a79-f6faa8c30f89).
2. If the template you're working on fits within an existing page, create a new artboard and add it to that page. If it doesn't fit into an existing page, create a new page and then add artboards from there.
3. Be sure to add all padding specific to that example in it's own folder within the layer list called "📐Padding" and hide it.
4. If the design variation is new and needs a spec, add it to the first artboard, add it's name (use the comment text style), and unhide the "📐Padding" group (see the template file for existing examples of how this is done now).
5. Add the labels **"Pre-release"** to artboards with symbols that haven't been implemented yet or **"Core-only"** to artboards with symbols that are available only in HTML. This info is usually added to the description of the issue.
6. Zip your file and attach it to the GitHub issue you were assigned to. Add a list of pages you added/edited and the artboards on those pages. Finally, tag @doruskova in your comment.
### Questions?
If you have any questions or concerns, please contact Marie Doruskova [mdorusko@redhat.com](mailto:mdorusko@redhat.com).
