---
# Leave the homepage title empty to use the site title
title: Course Program
date: 2023-07-19
type: landing

sections:
  - block: markdown
    content:
      title: My title
      subtitle: 'My subtitle'
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    content:
      title: My title
      subtitle: 'My subtitle'
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: markdown
    content:
      title: My title
      subtitle: 'My subtitle'
      text: {{< table path="sem1.csv" header="true" caption="Table 1: My results" >}}
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
---