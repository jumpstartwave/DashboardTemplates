# Dashboard Templater: Template Repo

This repository contains assets used by the Wave Labs Dashboard Templater. Although we (CPIO) curate this repo, we hope that the external community can contribute to this repo; we encourage people to create their own templates and send us a pull request.

_Note: if your organization is a bit more private, you can create your own template repo and point the Dashboard Templater to your own repo._

Right now, the Dashboard Templater tool (on the APEX/VisualForce side) only handles Github repos. We might build connectors for other repos in the future. (Or you can feel free to do so!)

### Template Defintion

Each template is comprised of two files: one .json and one .png.

The **.json** file contains three elements: templateName (the  name...), templateDescription (a short description of the template), and state (the JSON blob defining the template layout).

The **.png** file is simply a thumbnail image for the template. Thumbnail dimensions are 160px (width) by 100px (height).

### Template JSON

A template **.json** file has the following structure:
```sh
{
    "templateName": "some string",
    "templateDescription": "some description",
    "state" : {
        // your layout definition
    }
}
```

### Questions?

Any feedback? Go to jumpstartwave.com and feel free to contact us!