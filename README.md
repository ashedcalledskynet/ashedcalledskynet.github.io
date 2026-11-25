# Dyadica Jekyll theme

Private starter repository. Use GitHub's Use this template feature to create independent sites.

## Local development
Install Ruby 3.3 and Bundler, then run `bundle install` and `bundle exec jekyll serve`.

## Configuration
Edit `_config.yml`: title, description, url (canonical origin), baseurl (empty for root or /repository), heading_prefix, heading_highlight, heading_suffix, home_intro, blog_intro, privacy, privacy_url, disclaimer_url, favicon, social_links (name, icon, username, url), paginate, paginate_path, show_excerpts, related_posts_settings (max_posts, min_common_tags), permalink and category_path. Restart Jekyll after changes. Category page permalinks and pagination directory must match the configured paths.

Replace demo posts, categories, images and About page. Replace privacy and disclaimer placeholders with accurate site-specific policies before publication. YouTube embeds use `{% include youtube.html id="VIDEO_ID" %}` and load only after activation.

Layouts live in `_layouts`, components in `_includes`, styles in `_sass/theme`, navigation data in `_data`, assets in `assets`. Keep third-party notices.

## Deployment
The Pages workflow is manual only. Do not enable Pages for the private template itself. Configure Pages for a new site deliberately, verify visibility and canonical URL, then run the workflow manually.
