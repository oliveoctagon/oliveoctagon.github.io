# Olive Octagon Website

- Jekyll
- Tailwind CSS v4
- GitHub Pages

# Quickstart

Just run `npm run dev` while developing.


# Jekyll

To build the Jekyll site
```
bundle exec jekyll build
```

To serve the Jekyll site and watch for changes
```
bundle exec jekyll serve --livereload
```

# Tailwind v4

Tailwind must compile before push
```
npx @tailwindcss/cli -i ./assets/css/style.css -o ./assets/css/tw.min.css --minify
```

To watch and auto compile when anything changes
```
npx @tailwindcss/cli -i ./assets/css/style.css -o ./assets/css/tw.min.css --minify --watch
```

npm must be installed to use tailwind.

# Watch while developing

```
npm run dev
```

- `dev` command is defined in package.json
- combines the Jekyll watch + tailwind watch commands
- quit with `ctrl + c` x3


# Notes

- This file's name starts with an underscore so Jekyll will ignore it