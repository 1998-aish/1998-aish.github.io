# Aishwarya Srivastava · Portfolio

Source for **https://1998-aish.github.io**.

- `index.html`: the whole site (no build step, no framework). Dark/light theme, role filter for projects, contact form that opens an email draft.
- `assets/img/`: project images, taken from each project's repository
- `assets/Aishwarya_Srivastava_Resume.pdf`: résumé download (phone number removed for the public copy)

To update a project, edit its `<article class="card project">` block in `index.html`. The `data-roles` attribute (`ds`, `an`, `sw`, `se`) controls which role filters show it. Push to `main` and GitHub Pages republishes automatically.
