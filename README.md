# Lloyd Lab website

A plain static site (HTML + one stylesheet + images). No build step and no server needed.

## Put it online with GitHub Pages (free)

1. Sign in at github.com (or create a free account).
2. Click **New repository**. Name it e.g. `lloydlab`, make it **Public**, and create it.
3. On the empty repository page, click **uploading an existing file**. Drag in everything from this folder
   (all the `.html` files, `style.css`, and the `images` folder). Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
5. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/lloydlab/`.

## Use your own domain (optional, ~£10–15 a year)

1. Buy a domain from any registrar (e.g. lloydlab.org).
2. In the repository, **Settings → Pages → Custom domain**: enter the domain and save.
3. At the registrar, add the DNS records GitHub shows you (its help page "Managing a custom domain for your GitHub Pages site" lists them). Tick **Enforce HTTPS** once it becomes available.

## Leaving Wix

Only cancel the Wix plan once the new site is live and you've checked every page. All the images used here have already been copied out of Wix into the `images` folder.

## Making changes

Each page is a normal HTML file you can edit directly on GitHub (open the file, click the pencil icon, commit). Or ask Claude to make the change and upload the updated file.
