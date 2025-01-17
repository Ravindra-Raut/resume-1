[![Netlify Status](https://api.netlify.com/api/v1/badges/a0c0eebc-5732-4289-b794-2d61543c0636/deploy-status)](https://app.netlify.com/sites/ravindra-raut-resume/deploys)

# My resume created in R with Pagedown

This repo has all the code and data to render my resume in R with [pagedown package](https://pagedown.rbind.io)

The main files are:

- 'update_resume.R' : R script that renders the Rmarkdown document twice, once for HTML version and once for PDF version. This ensures both versions are always the same.
- 'resume.Rmd': Source template for both the PDF and HTML versions, based on the YAML Paramater doctype
- 'index.html': The final output of the template when the parameter doctype is set to HTML.
- 'mleary_resume.pdf': Result for single page PDF file. Note, this version has a different CSS styling sheet and is in black and white for more consistent printing.
- 'mleary_resume.html': HTML output that is used to save off pdf version.
- 'data/': CSV files with my work and skills data.  I originally used an excel file, but moved this direction to make it easier to use outside of windows.
- 'css/': Directory containing the custom CSS files used to tweak the default 'resume' format from pagedown.

Shout out to Nick Strayer, whose code was the basis for my format. I heavily borrowed from his code and approach. See the original here http://nickstrayer.me/cv/


# To Do List

I want to adjust how I store my career info.  More to follow, but is works for now.
