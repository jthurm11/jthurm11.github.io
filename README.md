# GitHub Pages Repository

Welcome to my GitHub Pages repository! This repository hosts a static website generated using [Jekyll](https://jekyllrb.com/) and published via [GitHub Pages](https://pages.github.com/).

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository contains the source code for my personal website, built with Jekyll and hosted on GitHub Pages. The website includes information about me, my projects, my resume, and a blog.

## Setup

To set up the website locally on your machine, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/jthurm11/jthurm11.github.io.git
    cd jthurm11.github.io
    ```

2. **Install Jekyll and Bundler**:

    Make sure you have Ruby and Bundler installed. Then, install Jekyll and other dependencies:

    ```bash
    gem install jekyll bundler
    bundle install
    ```

3. **Run the website locally**:

    ```bash
    bundle exec jekyll serve
    ```

    Open your browser and navigate to `http://localhost:4000` to see your website.

## Usage

### Viewing the Website

You can view the live website at [https://jthurm11.github.io/](https://jthurm11.github.io/).

### Editing the Website

To update the content of the website, edit the files in the `_data`, `_posts`, `_includes`, and `_layouts` directories. Key files include:

- `_data/navigation.yml`: Contains the navigation menu items.
- `_posts/`: Contains blog posts.
- `_includes/header.html`: Contains the header section.
- `_includes/footer.html`: Contains the footer section.
- `_layouts/default.html`: The main layout file.

After making changes, commit and push them to your GitHub repository to update the live site.

## Customization

You can customize the look and feel of your website by editing the CSS and HTML files. The main CSS file is located at `assets/css/style.scss`.

To change the theme or layout:

1. Modify the `_config.yml` file to update the site configuration.
2. Edit the `_layouts` and `_includes` files to customize the HTML structure.
3. Update the `assets/css` files to change the styling.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please create an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the GNU GPL v3 License. See the [LICENSE](LICENSE) file for details.

---

Thank you for visiting my website repository!
