# Bluepaper

This repo contains the raw text files for each Bluepaper syllabus.

Compile using the following:

    # Convert to .texi
    pandoc --shift-heading-level-by=-1 -o output.texi front-end.md

    # Build HTML files
    texi2any --html output.texi

