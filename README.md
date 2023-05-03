# Let's create a blog!

## Set up:

1. Fork the following repo: https://github.com/chrisrhymes/example-blog
2. Name your repo “your-username.github.io” where your-username is your GitHub username
3. From the forked repo, click the “Code” dropdown.
4. Select the “Codespaces” tab
5. Click “Create codespace on master”
6. Open the terminal using the top left menu.
   - View
   - Terminal
7. In the terminal run “bundle install”
8. Then run `bundle exec jekyll serve` and click the “Open in browser” button.
9. View your new site.
10. Press `ctrl + c` in the terminal window to stop serving your site

## Edit the Configuration

1. Edit the `_config.yml` file
2. Update the title and description for your site. The title appears in the top left of the site as the home link
3. Run `bundle exec jekyll serve` and click the “Open in browser” button to see your changes.

## Create an author page:

1. In the `_authors` directory, copy `example.md` to `your-name.md` where your-name is your name, such as `chris.md`
2. Edit `your-name.md` and change the title, name, position, description, website and social links (comment out any social links you don’t want to show)
3. Remove the content after the --- and type a bio about yourself. The content uses [markdown](https://www.markdownguide.org/cheat-sheet/).
4. Choose an image for your avatar or create an avatar with https://getavataaars.com/ ensuring that the filename is all lowercase and has no special characters or spaces.
5. Drag and drop the image into the img folder.
6. Update the avatar setting to point to your new image
7. Save your changes
8. Update the post in the `_posts` folder so the author is the same as the name setting in `your-name.md`
9. Visit the browser window with the website running and click on the Authors link in the top right of the page. It should now show your author in the list. Click through to see your author page

## Creating a post:

1. Copy the existing post in `_posts` folder with the naming convention is `YYYY-MM-DD-post-name.md`
2. Update the title, date, and categories. Ensure the author is your author name
3. Delete everything under the last --- and write your blog post using [markdown](https://www.markdownguide.org/cheat-sheet/)
4. Save the changes
5. Visit the browser window with the website running and click on the title in the top left to go back to the home page. Your new post should now be visible. Click to view it.

## Committing changes:

1. Click the Source control button on the left menu bar
2. Enter a commit message
3. Press the `+` symbol on the right of the Changes heading
4. Press the drop down next to the `Commit` button and select `Commit and push`

## Making your site live:

1. In GitHub, navigate to the repository
2. Click the `Settings` tab
3. Click on the `Pages` option under `Code and automation`
4. Select `Deploy from a branch`
5. Then select the `main` branch and the `/ root` directory, then press Save
6. Your site will then build and will soon be available on `https://your-username.github.io` where your username is your github username.
