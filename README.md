![University of New Haven CIT Banner Logo](https://hack.newhaven.edu/images/unh_logo_banner.png)

## Penetration Testing Report Template 

This repository is a template that can be used by anyone for writing Penetration Test reports. This example was solely created for an example in LaTeX. The reason for this is management for LaTeX is much easier for larger document (e.g managing references). This template has been used over the years for [GlobalCPTC](https://cp.tc/) and has made our reports standout.

Other penetration test reports can be found at GlobalCPTC's [GitHub](https://github.com/nationalcptc/report_examples). By no means is this report template is perfect but it meant to help people who are not familiar with LaTeX learn it. After gaining familiarity with LaTeX you will most likely not want to use Microsoft Word ever again. We hope this is helpful!

## Usage
You can use a local compiler for this document however, collaboration is usually important if you plan to use this for an ethical hacking class or competition. [Overleaf](https://www.overleaf.com) is a free online LaTeX editor that provides many functionalities to enable editing LaTeX documents with ease.

This template is structured so you *should not* need to edit any tex files outside the `tex/` directory. The contents of the tex files that are likely to need modification outside said directory can be configured with the `tex/config.tex` file. This config file also has a few custom commands within it which can be used to auto fill common phrases, such as the client name and acronym (`\client` and `\cptc`). If are new to LaTeX, you should note that to have a space after an instance of one these commands, you will need to escape the space with a `\` (For example. `\cptc\ ` rather than `\cptc `).

## Main Contributors 
- Tyler Balon - Was the original creator of this template. [GitHub](https://github.com/tjbalon)
- Samuel Zurowski - Modified this template over the years mainly using CVSS and proper vulnerability scoring. [GitHub](https://github.com/samuelzurowski)
- Charles Barone - Restructured template to add automated commands and general usability improvements. [GitHub](https://github.com/CharlesBarone)

## License
This template is distributed under the MIT License.
