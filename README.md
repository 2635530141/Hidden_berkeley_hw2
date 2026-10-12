# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

This guide is for people who are new to Berkeley, especially incoming graduate students, who want to find campus and city resources that are easy to miss in a first semester. Each entry gives a short access note and a link to the resource's official page, so readers can confirm current hours and eligibility before they go.

## Website checks

Live website: https://2635530141.github.io/Hidden_berkeley_hw2/


Improved entry: Morrison Library (HB03). Its access note now says it is open to the public in 101 Doe Library, allows no laptops (reading tablets are fine), and requires a UC Berkeley library card for borrowing. Its link now goes to the Morrison Library page instead of the Library homepage.
New resource: Tool Lending Library (Berkeley Public Library), HB09.
What was checked (October 11, 2026): after the Pages build from main and /docs, the published page shows the new heading and introduction and all nine resources in CSV order. Every displayed name, category, area, and access note matches docs/_data/locations.csv, and all nine "Official source" links open the intended official pages.