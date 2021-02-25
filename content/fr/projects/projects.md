---
#widget characteristics
widget: portfolio
headless: true
active: true
weight: 60

title: "Projects"

content:

# displaying the projects in the project file
  page_type: project

#Filter toolbar (optional).
#Add or remove as many filters ([[content.filter_button]] instances) as you like.
#To show all items, set tag to "*".
#To filter by a specific tag, set tag to an existing tag name.
#To remove toolbar, delete/comment all instances of [[content.filter_button]] below.
#Default filter index (e.g. 0 corresponds to the first [[filter_button]] instance below).

  filter_default: 0
  
  filter_button:
    - name: All 
      tag: "*"
    - name: History of Macroeconomics 
      tag: History of Macroeconomics
    - name: Research Project 
      tag: Research Project
    - name: R
      tag: R
    - name: R Package
      tag: R Package

design:

#Choose how many columns the section has. Valid values: 1 or 2.
  columns: "1"

# Types of page layout
  view: 3

# For showcase view, flip alternate rows?
  flip_alt_rows: true
---

