# Building the website locally

The website for the workshop, https://unidata.github.io/pyaos-ams-2021/index.html, is generated from Markdown using Sphinx.
If you are using conda, you can follow these steps while inside the `site/` directory to build the website locally:

1. Create the conda environment:
   ```
   conda env create -f site-environment.yml
   ```

2. Activate the environment:
   ```
   conda activate pyaos-ams-2021-site
   ```

3. Build the docs
  - in a unix/mac environment:
    `make html`
  - in windows environment:
    `.\make html`

The site will be located in the `build/html/` directory.
Open `build/html/index.html` in your browser and stand back in awe!

To clean up the generate files, run `make clean` or `.\make clean`.
