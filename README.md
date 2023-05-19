# 🏗️ Let's create a blog!

## ⚙️ Set up:

1. Fork the following repo: https://github.com/chrisrhymes/example-blog
2. Name your repo “your-username.github.io” where your-username is your GitHub username
3. From the forked repo, click the “Code” dropdown.
4. Select the “Codespaces” tab
5. Click “Create codespace on main”.
6. Open the terminal using the top left menu.
   - View
   - Terminal
7. In the terminal in the bottom right of the window, enter `bundle install` and then press enter to run it.
8. Then enter `bundle exec jekyll serve` and press enter.
9. Click the “Open in browser” button in the pop-up that appears
10. View your new site.
11. Click into the terminal window and press `ctrl + c` to stop serving your site.

## ✍️ Edit the Configuration:

1. Edit the `_config.yml` file
2. Update the title and description for your site. The title appears in the top left of the site as the home link. The description is used as a meta tag to describe your site to search engines.
3. In the terminal window, enter `bundle exec jekyll serve` and press enter.
4. Click the “Open in browser” button in the pop-up that appears

## 📝 Create an author page:

1. Open the `_authors` directory, right click on the `example.md` file and select "Copy" from the menu; right click on the `_authors` directory and select "Paste" to drop a copy of the file into that directory (it will be called `example copy.md`).
2. Right click `example copy.md` and select "Rename" from the menu; call it `your-name.md`, where your-name is your name, (e.g. chris.md).
3. Edit the your-name.md file and change the information in the title, name, position, description, website lines, and social media links (comment out any social links you don’t want to show by typing `#` and a space before the ones you don't want to display; they will turn grey to show they are commented out).
4. Remove the content after the last `---` and type a bio about yourself. The content uses [markdown for formatting](https://www.markdownguide.org/cheat-sheet/).
5. Choose an image for your avatar or create an avatar with https://getavataaars.com/ ensuring that the filename is all lowercase and has no special characters or spaces.
6. Drag and drop the image into the `img` folder.
7. Update the avatar setting to point to your new image.
8. Save your changes.
9. Edit the post called '2023-05-03-welcome-to-jekyll.markdown' in the `_posts` folder so the author is the same as the name setting in `your-name.md`.
10. Visit the browser window with the website running and click on the Authors link in the top right of the page. It should now show your author in the list. Click through to see your author page.

## 📬 Creating a post:

1. Like you did before, copy the '2023-05-03-welcome-to-jekyll.markdown' file in the `_posts` folder and paste it back into the same folder; it should appear as '2023-05-03-welcome-to-jekyll copy.markdown'; rename this file following the format `YYYY-MM-DD-post-name.md`.
2. Update the title, date, and categories. Ensure the author is your author name.
3. Delete everything under the last `---` and write your blog post using [markdown](https://www.markdownguide.org/cheat-sheet/).
4. Save the changes.
5. Visit the browser window with the website running and click on the title in the top left to go back to the home page. Your new post should now be visible. Click to view it.

## 🚀 Committing changes:

1. Click the Source control button on the left menu bar.
2. Enter a commit message.
3. Press the `+` symbol on the right of the Changes heading.
4. Press the drop down next to the `Commit` button and select `Commit and push`.

## 🎉 Making your site live:

1. In GitHub, navigate to the repository.
2. Click the `Settings` tab.
3. Click on the `Pages` option under `Code and automation`.
4. Select `Deploy from a branch`.
5. Then select the `main` branch and the `/ root` directory, then press Save.
6. Your site will then build and will soon be available on `https://your-username.github.io` where your-username is your github username.
