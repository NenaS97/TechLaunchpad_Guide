# TechLaunchpad_Guide

A guide for navigating the tech job search process, covering roles, skills, job platforms, resume writing, and interview preparation.

## About This Project

This guide was built using the Darwin Information Typing Architecture (DITA) standard. The content is authored in modular XML files following DITA principles, allowing for structured and reusable information.

## Technical Elements and Attributes Used

The DITA source files in this project primarily utilize the following elements and attributes for structure and content:

* **`<reference>`:** Used for presenting structured reference information.
* **`<task>`:** Used to describe step-by-step procedures.
* **`<topic>`:** Used for general conceptual content.
* **`<title>`:** For defining titles.
* **`<shortdesc>`:** For providing brief descriptions.
* **`<refbody>`, `<taskbody>`, `<conbody>`:** As the main content containers.
* **`<section>`:** For organizing content into logical parts.
* **`<p>`:** For standard paragraphs of text.
* **`<ul>`, `<li>`:** For creating bulleted lists.
* **`<cmd>`:** To specify actions the user needs to take in task topics.
* **`<info>`, `<result>`, `<prereq>`, `<postreq>`:** To provide details and context in task topics.
* **`<xref>`:** To create links to other content and external resources, use the `<scope>` attribute to indicate the link target.
* **`<b>`:** For bold text formatting.

The DITA source files were processed using the **DITA Open Toolkit (DITA-OT)** to generate the HTML5 output.

## View the Guide

To view the live version of this guide, visit [TechLaunchpad Guide](https://nenas97.github.io/TechLaunchpad_Guide/).

This site is automatically generated from the DITA source files in this repository. The generated content is hosted via GitHub Pages for easy access.

## Generating the Output

To regenerate the output site:

1. Run `dita --input=topics/ --output=outputs/`
2. Copy the HTML and CSS files to the `docs/` folder.
3. Commit and push the changes to GitHub for the site to update.

**Note:** The content within this personal project was AI-generated.
