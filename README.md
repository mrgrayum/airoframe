Airoframe Size Finder

A lightweight GitHub Pages web tool that helps customers determine the correct Airoframe product size based on PDGA-approved disc specifications.

Live Site

https://YOURUSERNAME.github.io/REPONAME/

What This Tool Does

Users can:

Select a manufacturer

Select a disc model

See recommended:

Airoframe Wall Hanger size

Airoframe Custom Mount size

The tool uses PDGA disc specification data and automatically determines compatibility based on:

Inner diameter (mm)

Outer diameter (mm)

Compatibility Rules

Airoframe Wall Hanger

Compatible inner diameter range: 159–194mm

Airoframe Custom Mount

Inner diameter must be ≥159mm

Outer diameter must be ≤230mm

If a disc falls outside those ranges, the tool displays:
“Disc Selected Is Incompatible” for that specific product only.

Files in This Repo

index.html — main site

discs.json — PDGA disc data source

Updating Disc Data

When a new PDGA CSV is available:

Convert CSV to updated discs.json

Replace the existing discs.json

Commit changes

GitHub Pages auto-updates
