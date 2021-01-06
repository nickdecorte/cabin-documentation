# Setup Cabin

1. Create directory named cabin
2. Create new Strapi project named admin in cabin directory
3. Checkout cabin-plugin-pages as pages in the plugin directory of Strapi
4. Checkout cabin-site as site in cabin directory
5. Checkout cabin-theme as theme in cabin directory
6. Checkout cabin-workers as workers in cabin directory
7. Generate site with worker like 'node index site'
8. Generate thumbnails with worker 'node index thumbnail'
9. Symlink in public folder of Strapi project to the site directory by 'ln -s ../../site/ site'
10. Symlink in public folder of Strapi project to the theme directory by 'ln -s ../../theme/ theme'
11. Run 'npm run develop' in Strapi project

After executing previous steps, you should be able to navigate to http://localhost:1337/admin and create a website with checked out site and themes via live content builder.