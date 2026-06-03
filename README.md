# Enya Sandvold-Olsen, Portfolio Website

A refined, image-first architecture portfolio in a light editorial style, drawing on the
practices Enya admires (Peter Barber, Joseph Dirand, Tsuruta).

## What it does
- Caption-free gallery grid. Project title, number and type reveal on hover as an overlay,
  with a "View project" cue.
- Gallery / List toggle, placed in the top navbar.
- Project pages use a two-column layout. The left column shows one large lead image followed by
  a vertical trail of the remaining images. The right column holds the written information
  (number, title, description, Program, Type, Location, Year) and stays in view as you scroll
  the images, with Previous / All Work / Next links.
- Profile and Contact pages.
- Paper grain, refined Fraunces and Albert Sans typography, smooth motion throughout.
- Fully responsive, fits one screen on the landing. No build step, no server. Just open index.html.

## How to add the images
1. Drop the real image files into the **images/** folder.
2. Name each file EXACTLY as listed below (the site already references these names).
3. Reload. Any image not yet added shows a labelled placeholder, so the site stays usable
   while you fill it in.

## Image manifest (which file goes where, cover listed first)

01 Study Set
1.png, 2.png, 3.png, 4.png, 5.png, 6.png, 7.png, 8.png, 9.png, 10.png, 11.png, Extra+Credit+[Converted].png

02 Precedent Study, ARC 107
Section 1 finale.png, plan.png, photo 1.jpeg, photo 2.jpeg, photo 3.jpeg, Photo done.jpeg, Photoshop 1.jpeg, IMG_6202.JPG
(also in that email: Plan 2 Final RH.pdf, Section 1.pdf, the ARC 107 Precedent Study PDF, IMG_6204.JPG via Drive)

03 Community Center
Render 1.png, Render 2.png, Render 3.png, CAC 1.png, CAC 2.png, CAC 3.png, CAC 4.png, CAC 5.png, CAC 6.png

04 Chair
chair 1.jpg, chair  2.jpg, chair 3.jpg, chair 4 .jpg, Measurements and Assembly Diagram.png, picture.png
(Drive raws: Studio Session-207/215/219.CR3, Studio Session-221_edited.jpg)

05 Structures and Sustainability
Structures A.png, Structures B.png, Structures C.png, Structures D.png, Structures E.png, Stuctures Community Center1 .png, Stuctures Community Center 2 .png, Sustainability.png

06 Tube House
Tube house.png, Tube house 1.png, Tube house 2.png, Tube house_Page_1.png

07 House in Sakuradai
Portfolio House in sakuradai.jpeg, S1.png, S2.png, house in.jpeg, house in sakuradai.jpeg, House in Sakuradai 2.jpeg, Diagram 1.png, Diagram 2.png, Diagram 3.png, Diagram 4.png, Diagram 5.png, Plan 1 (1).png, Plan 2 (1).png

08 Sakuradai, Final
Project 1_Page_1.png through Project 1_Page_7.png, House in sakuradai 1.jpeg, bswood.jpeg, a.png, b.png, c.png, d.png

## Notes
- Keep filenames exactly as written, including quirks like the double space in "chair  2.jpg"
  and the spelling "Stuctures", or the site will not find the file.
- Edit titles, order, metadata, and image lists in projects.js (one object per project).
- Edit Profile / Contact wording in about.html and contact.html.

## Files
- index.html ........ home grid with hover overlays and view toggle
- project.html ...... project view (driven by ?id=)
- about.html ........ profile
- contact.html ...... contact
- projects.js ....... all project data and image lists
- style.css ......... styling
- images/ ........... drop image files here
