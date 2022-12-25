# RatingsSliderSkeleton
A skeleton of PCIbex code for an acceptability ratings task, with vertical sliders that have been specially formatted in CSS.

# Notes
To use this for an experiment, you should…

* …edit `chunk_includes/consent.html`
* …edit the completion screen in `data_includes/main.js` to have the right final details (e.g. any URL to validate completion with e.g. Prolific)

Some customized CSS for this experiment has…

* …made PCIbex better at being mobile-responsive (`css_includes/global_main.css`)
* …customized slider bars (`css_includes/global_main.css`)

Other file dependencies…

* consent.html (the consent form; `chunk_includes/consent.html`)
* targetItems.csv (target sentences, with different groups seeing different lists; `chunk_includes/targetItems.csv`)
* controlItems.csv (controls used by all participant groups; `chunk_includes/controlItems.csv`)
