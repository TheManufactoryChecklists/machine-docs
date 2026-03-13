# Machine Documentation for The Manufactory

This repository organizes machine documentation by room, mirroring the physical layout of **The Manufactory – Cincinnati’s Makerspace** (TM).  Each room's folder has sub-folders for the applicable machines in that room.  In each sub-folder, there's a markdown file for that machine with safety info, limitations, maintenance & servicing requirements, operating procedures, emergency procedures, and a link for further study (a URL to the same sub-folder).

These markdown files will become sub-pages on TM's website (again organized by room).  The goal is to make information easy to find, easy to understand, easy to use, and easy to maintain.  Members are expected to use their preferred browser to familiarize themselves with each machine prior to use.  Their preferred AI (typically on their phone) can use this context to answer questions.

## Repository Structure

### Top Level Folders

The first folder contains the markdown templates we use;

- **templates/** — A template for machine documentation, another for lessons learned, and a README.md file (read before creating folders or content therein).

The remaining top-level folders match TM's rooms, and contain the sub-folders for each machine therein;

- **electronics/** — Soldering stations, oscilloscopes, power supplies
- **grinding/** — Surface grinders, pedastal grinder, tool grinder, sand blast cabinet, presses
- **lasersplastics/** — Lasers, vinyl cutter, vacuum former
- **metalshop/** — CNC mill, Bridgeport mills, horizontal mill, lathes, drill presses, saws, bending, shearing, and other metalworking equipment
- **textiles/** — Sewing machines, sergers, heat press
- **welding/** — CNC plasma table, MIG, TIG, Oxy, spot welders
- **woodshop/** — CNC router table, table saws, jointer, planer, bandsaws, and other woodworking tools

### Sub Folders

Each machine specific sub-folder will have the edited template file (.md), PDFs, image files, etc., for that machine.  Everything TM knows about that machine will be in that folder.  This makes that folder's URL an excellent resource for AI.

Each machine has a dedicated `.md` file (GitHub Flavored Markdown file, GFM) inside its sub-folder.  After review and approval, it's converted to mobile-friendly HTML for display on TM's website.  Members view these pages prior to using a machine.  These files also contain a link (URL) designed to help the member's preferred AI answer questions about using that machine.

## Purpose and Scope

This repository is **public** so that:

- Members can reference source documentation easily (although they typically consume it via our website)
- Instructors and maintainers can collaborate on what gets published to our website
- External makers can learn from or contribute improvements
- Forks and pull requests are welcome

## Contributing

Contributions that improve clarity, safety, or usability are welcome.

When submitting changes:

- Keep formatting consistent with the templates
- Use clear, direct language
- Add pictures, OEM manuals (PDFs), links to OEM website, etc.
- Follow the existing folder structure

Pull requests will be reviewed by maintainers.

## Contact

For questions about this documentation, or access to the makerspace, please contact:

**[https://themanufactory.us](https://themanufactory.us)**
