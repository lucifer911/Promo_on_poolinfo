# How to Submit Your Pool Promotion Request
Follow these steps to submit your pool for promotion on our platform:

## Step 1: Fork the Repository
1. Visit the GitHub repository URL (provide the link to your GitHub repo here).
2. In the top-right corner of the page, click the "Fork" button.
3. This will create a copy of the repository in your own GitHub account.

## Step 2: Update the promo.json File
1. Navigate to the promo.json file in your forked repository.
2. Click on the file to open it, then click on the pencil icon (Edit) in the upper right corner to edit the file.
3. Replace the existing content with your pool's information using the JSON format provided below:

```
{
  "poolName": "pool name",
  "poolTicker": "ticker",
  "Website": "https://yourwebsite.com",
  "socialLinks": {
    "twitter": "https://twitter.com/examplepool",
    "telegram": "https://t.me/examplepool",
    "discord": "https://discord.gg/examplepool"
  },
  "description": "This is a short description of Example Pool. It has numerous features and benefits that make it stand out in the Cardano space."
}
```
Make sure to replace the placeholders with your actual pool data. Keep the JSON structure intact to avoid any errors.

1. After editing, scroll down to the "Commit changes" section.
2. Enter a commit message that describes your update, for example, "Update promo.json with Your Pool Name".
3. Choose the option to "Commit directly to the main branch" if you have no other branches in your fork.
4. Click the "Commit changes" button.

## Step 3: Submit a Pull Request
1. Once you have committed your changes, navigate to the "Pull requests" tab in the original repository (not your fork).
2. Click the "New pull request" button.
3. Click on "compare across forks" link.
4. Ensure that the base fork is set to the original repository's main branch, and the head fork is set to your fork's branch where you made the changes.
5. You should see your commit(s) in the comparison. If everything looks correct, click the "Create pull request" button.
6. Enter a title for your pull request, such as "Promotion Request for [Your Pool Name]".
7. Optionally, write a brief description of your pool and why you'd like to promote it.
8. Click the "Create pull request" button to submit the request.

Your pull request will now be reviewed, and if accepted, your pool information will be promoted on our platform according to the promotional schedule.
