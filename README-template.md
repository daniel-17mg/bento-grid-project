# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview
I recently completed a Bento Grid project, which challenged me to design and structure a flexible grid-based layout inspired by the clean and modular "bento box" style. The project involved organizing content into multiple grid sections while maintaining a visually balanced and user-friendly design.

One of the most valuable lessons I gained from this project was responsiveness. Building the grid required me to think beyond a static layout and adapt the design to different screen sizes. I had to carefully use CSS grid, flexbox, and tailwind media queries to ensure that the layout adjusted seamlessly on mobile, tablet, and desktop views.

### The challenge
Throughout the project, I faced several challenges:

- Responsiveness: Making the layout adjust smoothly across mobile, tablet, and desktop screens required trial and error with breakpoints, media queries, and flexible units.

- Using Grid and Flexbox Together: Combining CSS Grid for the overall structure with Flexbox for internal alignment was tricky at first, especially when deciding when to use one over the other.

- Order Property: I also struggled with rearranging elements using the order property. At times, elements overlapped or didn’t behave as expected, but through experimentation, I learned how to control positioning more effectively.

- Despite these challenges, the project was a huge learning experience. It taught me how powerful responsive design techniques are and helped me build confidence in using grid, flexbox, and order to create flexible layouts.

### Screenshot

![Project screenshot](./assets/images/screenshot_29-8-2025_103944_127.0.0.1.jpeg)

### Links

- Solution URL: [Add solution URL here](https://daniel-17mg.github.io/bento-grid-project/)
- Live Site URL: [Add live site URL here](https://daniel-17mg.github.io/bento-grid-project/)

## My process

1. Project Setup

I started by creating the project with HTML for the structure and used Tailwind CSS as my styling framework to speed up development and maintain consistency.

2. Layout Planning

Before coding, I outlined the grid sections I wanted, similar to a bento box style layout.

3. Building the Layout

I used a combination of CSS Grid and Flexbox:

Grid was used to create the overall structure of the bento grid (rows and columns).

Flexbox was used inside some grid items to align content neatly.

4. Responsiveness

To make sure the layout looked good on all devices, I added Tailwind responsive classes (like md:grid-cols-2, lg:grid-cols-4, etc.).

On desktop, the layout displays multiple columns.

On tablet, the number of columns reduces for readability.

On mobile, everything stacks into a single column for easy scrolling.

5. Challenges & Learnings

I faced challenges combining Grid and Flexbox effectively. At first, some sections didn’t align as expected.

I also struggled with the order property when rearranging items across breakpoints, but through trial and error I learned how to control it.

Making the layout fully responsive was tricky, but I gained confidence in using Tailwind’s responsive utilities.

### Built with

- Semantic HTML5 markup
- Tailwind custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Working on this project taught me several important skills:

- Responsiveness with Tailwind CSS → I learned how to make layouts adapt to different screen sizes using Tailwind’s responsive classes (sm:, md:, lg:, etc.), ensuring the design works well on mobile, tablet, and desktop.

- Structuring layouts with Grid and Flexbox → I gained hands-on experience combining CSS Grid for the overall page structure and Flexbox for aligning content inside individual sections. This helped me understand when to use each approach.

- Using the order property → I practiced rearranging elements at different breakpoints with the order utility in Tailwind. At first, it was challenging, but I learned how to control the flow of elements effectively across devices.

### Continued development

While building this project, I realized there are still areas I want to improve on:

- Advanced Responsiveness → I’d like to practice more with complex breakpoints and layouts, ensuring my designs remain pixel-perfect across all devices.

- Deeper Grid & Flexbox Mastery → Although I got comfortable using Grid for structure and Flexbox for alignment, I want to explore more advanced layout patterns and refine my decision-making on when to use each.

- Order & Content Flow → I plan to get more confident using the order property and other responsive utilities in Tailwind to handle content rearrangement in a cleaner way.

- Reusable Components → In the future, I want to focus on making my layout components more reusable and modular, which will make scaling larger projects easier.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/daniel-17mg)