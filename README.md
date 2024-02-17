[![Demo](demo.png)](https://digitalden.cloud)

<h1 align="center">Particles.js Integration Tutorial for HTML5Up Dimensions Site Template</h1>

<p align="center">
  <a href="https://youtube.com/playlist?list=PLfmMgg_VrrlAz4s0UxLCdgZlcw2iCqVrD">
    <img src="https://img.shields.io/badge/YouTube-Tutorial-red.svg" alt="Tutorial Series on YouTube">
  </a>
</p>

## Overview

This repository contains all the necessary files for integrating dynamic particle effects using particles.js into the HTML5Up Dimensions site template. Enhance the visual appearance of the site while maintaining its responsiveness and functionality. For detailed guidance, visit the YouTube tutorial.

- For a live demo of the integrated particle effects, visit [digitalden.cloud](https://digitalden.cloud)

## Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- Visual Studio Code or any preferred code editor.
- Live Server extension for Visual Studio Code (optional but recommended).

## Project Steps Overview

1. **Setup and Prerequisites:**

   - Download the Dimensions template from HTML5Up, available in this repository.
   - Open the site files in VS Code or another code editor of your choice.

2. **Integration Process:**

   - Retrieve `particles.min.js` from the particles.js directory in the repository.
   - Place the `particles.min.js` file into the `assets/js` directory of your website.
   - Append the contents of `index-with-particles.html` to your template's `index.html`.
   - Download and place the `particles-js.json` file into a newly created `assets/config` directory.

3. . **Resolving CSS Conflicts:**

   - Incorporate the necessary CSS from the repository to ensure compatibility with `particles.js`.
   - Append this CSS to your `main.css` in the `assets/css` directory.
   - To reveal your background image and allow the particle effects to overlay it, ensure the `#bg:after { display: none; }` rule in your CSS is commented out.
   - If you wish to change the background, update the `background-image` URL within the `#bg:after` selector to your preferred image.

4. **Customizing Particle Effects:**
   - Adjust the particle settings in the `particles-js.json` file within the `assets/config` directory.
   - Optionally, use the [particles.js online configuration tool](https://vincentgarreau.com/particles.js/) for real-time customization. Download your configuration and replace the content in your project’s config file.

## Credits

This project was made possible by the contributions of HTML5Up for their site templates and Vincent Garreau for creating the particles.js library.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contact

If you have any questions, feedback, please feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/digitalden/)
