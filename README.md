# blog
Decided to write ✍️

Checkout the blog at https://bhagat.me/blog/

## Running locally

1. **Install Ruby** (3.x recommended). Check with `ruby -v`.

2. **Install dependencies:**
   ```bash
   bundle install
   ```

3. **Serve the site:**
   ```bash
   bundle exec jekyll serve
   ```
   The blog will be at **http://localhost:4000/blog/** (the `/blog` base path comes from `baseurl` in `_config.yml`).

4. **Optional:** Live-reload while editing:
   ```bash
   bundle exec jekyll serve --livereload
   ```
