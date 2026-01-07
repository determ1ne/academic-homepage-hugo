# academic-homepage-hugo

![Preview](static/assets/images/etc/preview.png)

A GitHub Pages (Hugo) template for personal academic website ported from the original Jekyll version [luost26/academic-homepage](https://github.com/luost26/academic-homepage).
Click [here](https://luost.me/academic-homepage/) to see the demo.

## Running Locally

1. Install Hugo by following the instructions for your operating system from the official Hugo documentation: [https://gohugo.io/installation/](https://gohugo.io/installation/)

2. Clone your forked repository to your local machine.

3. Run the following command in the root directory of the repository:

   ```bash
   hugo server
   ```

4. Browse to the displayed URL (typically http://localhost:1313) to see the website.

## Multilingual Support

This template supports multilingual websites, but currently limited to English and Chinese.
To enable multilingual support:

1. Update the `config.toml` file to include your desired languages
2. Create language-specific data files in the `data/` directory (e.g., `profile.en.yml` and `profile.zh.yml`)
3. Create language-specific content files with `.lang.md` suffix (e.g., `_index.en.md` and `_index.zh.md`)

## Customization

- Update `config.toml` for site-wide configuration
- Edit `data/profile.yml` for your personal information
- Modify `data/authors.yml` for author information
- Update `data/navigation.yml` for navigation menu
- Add publications in the `content/publications/` directory
- Add news items in the `content/news/` directory
