# Patternfly Design Kit
The PatternFly Design Kit is a collection of [Sketch](https://www.sketchapp.com/) assets that make it easy for designers to create high-fidelity design mockups that accurately represent [PatternFly](http://patternfly.org) components and layouts. It includes:

* A Sketch symbol library that includes components, icons, color palettes, and other PatternFly elements. Hosted on Sketch Cloud here: https://sketch.cloud/s/7do0P
* A template file that provides several starter layouts that will make it easier to construct common PatternFly screens. Hosted on Sketch Cloud here: https://sketch.cloud/s/nwY34

## Updating the kit
Sketch will automatically receive library updates in the top, right corner of an open Sketch file. You'll want to update the PatternFly library **and** update the symbols within your file (two separate notifications). You'll have to update **all** files that are using PatternFly symbols - it is not a one and done process, unfortunately.

To update you PatternFly Template file, open the updated template from your local repo and select **File > Save as Template...** This will replace the current template with the updated version and make the latest layouts available using the **New from Template...** feature.

Please check out our [announcements](https://github.com/patternfly/patternfly-design-kit/blob/master/Announcements.md) for important design kit update information!

## Filing bugs
If something isn't working as expected with the library or template file, please file an issue in this repo and label it with "bug". We should be able to fix it within a couple days! 

## Release notes
To check out the latest design kit release notes, go [here](https://github.com/patternfly/patternfly-design-kit/blob/master/PatternFly%20release%20notes.md).

## Contributing to the PatternFly Design Kit
We welcome contributions from our community of PatternFly designers. Please contact Gina Doyle (@gina) on the #patternfly-design-kit channel within the patternfly.slack.com Slack workspace.
### Contributing a new or edited symbol
Follow these steps:
1. Download the library file from here: https://sketch.cloud/s/7do0P
2. Create new symbols or edit symbols using the styles and elements from "Document"
**Be sure you take them from "Document" rather than "PatternFly"**
3. When naming a new symbol, follow the naming mechansim within that same category (ex. Forms / 2. Text Box / Success)
4. Make it clear which page in the file you edited and which symbols on the page you added/edited by adding a ⭐️ or some other mark to call them out.
5. Zip your file and attach it to the github issue you were assigned to. Add a list of the symbols you added/edited. And finally, tag @gdoyle1 in your comment.
### Contributing a new or edited template
Follow these steps:
1. Download the template file from here: https://sketch.cloud/s/nwY34
2. If the template you are working on fits within an existing page, create a new artboard and add it to that page. If it does not fit into an existing page, create a new page and then add artboards from there.
3. Be sure to add all padding specific to that example in it's own folder within the layer list called "📐Padding" and hide it.
4. If the design variation is new and needs a spec, add it to the first artboard, add it's name (use the comment text style) and unhide the "📐Padding" group. (Look in the template file for existing examples of how this is done now)
5. Zip your file and attach it to the github issue you were assigned to. Add a list of pages you added/edited and the artboards on those pages. And finally, tag @gdoyle1 in your comment.
### Questions?
If you have any questions or concerns, please contact Gina Doyle [gdoyle@redhat.com](mailto:gdoyle@redhat.com).
