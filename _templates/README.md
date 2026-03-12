# Add a machine

1. Fork the repository [Beginners Guide to Forking a GitHub Repo](https://dev.to/torirodgers/a-beginners-guide-to-forking-and-syncing-github-repositories-4kdk).
2. Open the *machine-template.md* file found in the **/_templates/** folder.
3. Use the **Save As** command to create the new sub-folder and file in the proper Room folder;
    1. Create a sub-folder which matches the machine name (one word; Make-Model).
    2. File name should be the same as the sub-folder (Make-Model), but start the file name with an underscore (_Make-Model), so that it's always listed first in that sub-folder.
    3. E.g. the **Grizzly 15" Planer** in the Woodshop is *\woodshop\Grizzly-G0453PX\_Grizzly-G0453PX.md*.
    4. This file will be the web page for this machine.
    5. The new sub-folder will provide context for AI to answer member questions.
4. Edit the template as required for that machine.
5. Commit, then Push, your changes (to save them to the cloud).
6. Create a Pull Request (to get your changes published).

## Content for each machine's folder

- Pictures of the machine
- OEM Manuals (PDFs)
- Edited machine template file (e.g. *_Grizzly-G0453PX.md*)
- Edited lessons learned template file (e.g. *_Grizzly-G0453PX-LL.md*)
- Other files (links to software, hardware, open-source info, etc.)

Everything in this sub-folder will provide context for AI when member's use it ask questions.

## Markdown Tools

- <https://copymarkdown.com/>
- OCRmyPDF → Pandoc (best for scanned or messy PDFs)
  - Run OCRmyPDF to convert the PDF into a text‑layered PDF
  - Run Pandoc to convert to Markdown
  