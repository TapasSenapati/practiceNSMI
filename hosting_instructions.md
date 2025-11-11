
# Hosting Your Interactive Quiz on GitHub Pages (for Free)

Follow these steps to get your quiz online and accessible via a public URL.

## Step 1: Create a GitHub Account
If you don't have a GitHub account, sign up for free at [https://github.com/join](https://github.com/join).

## Step 2: Create a New Repository
1.  Log in to your GitHub account.
2.  Click the `+` icon in the top-right corner and select `New repository`.
3.  Give your repository a name (e.g., `interactive-quiz`).
4.  Make sure the repository is set to `Public`.
5.  Click `Create repository`.

## Step 3: Upload Your Quiz Files
1.  In your new repository, click the `Add file` button and select `Upload files`.
2.  Drag and drop the `index.html`, `quiz.html`, and `equity_derivatives_quiz.json` files from the unzipped folder into the upload area.
3.  Click `Commit changes`.

## Step 4: Enable GitHub Pages
1.  In your repository, go to the `Settings` tab.
2.  In the left sidebar, click on `Pages`.
3.  Under `Build and deployment`, in the `Source` section, select `Deploy from a branch`.
4.  Under `Branch`, select `main` (or `master`) and keep the folder as `/(root)`.
5.  Click `Save`.

## Step 5: Access Your Live Quiz
-   GitHub will now build and deploy your site. This may take a minute or two.
-   Once it's ready, a green bar will appear at the top of the `Pages` settings screen with a link to your live site.
-   The URL will look something like this: `https://<Your-GitHub-Username>.github.io/<your-repository-name>/`
-   You can share this URL with anyone to access your quiz.

## Adding More Quizzes
To add a new quiz:
1.  Create a new JSON file for the topic (e.g., `new_topic_quiz.json`).
2.  Upload it to your GitHub repository.
3.  Edit the `index.html` file on GitHub and add a new list item with a link to the new quiz, like this:
    ```html
    <li><a href="quiz.html?topic=new_topic_quiz">New Quiz Topic</a></li>
    ```
