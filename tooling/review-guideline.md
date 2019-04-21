# Article Review Process Guideline

## Step 1: Create a new branch for your article

Create a new branch off `unibas-tilics/tilics/master` and name it
according to the following pattern:

    article-<articlenumber>-<name-of-the-article-lowercase-dashes>
    
For example, if an article has the number `73` and is called `Rice's
Theorem`, its corresponding branch name would be
`article-073-rices-theorem`.  Please not the leading zeros (padded to
3 digits) and the removed special characters, such as `'`.

## Step 2: Add your article

Create a Markdown file in the `articles` directory in the branch you
just created.  The name of the file follows the same pattern as the
branch name, except that it ends with an `.md` extension.  Thus, in
the example above, the file would be named
`article-073-rices-theorem.md`.  Please use the template below and
keep the `<!-- BEGIN ... -->` and `<!-- END ... -->` lines intact;
they are required for making the document more machine-readable.


```markdown
<!-- BEGIN TITLE -->
# Put your title here, including the leading pound sign
<!-- END TITLE -->

<!-- BEGIN BODY -->
Put your article's text in Markdown here.
<!-- END BODY -->


![Image title](../images/image-NUMBER-NAME-OF-ARTICLE.svg)


## Optional text
<!-- BEGIN OPTIONAL -->
If your article has some optional text, add it here.
<!-- END OPTIONAL -->



## Author
<!-- BEGIN AUTHOR -->
Put your name (and only your name) here.
<!-- END AUTHOR -->
```

Please put your image draft for the artist(s) to the `images` directory.
The file should have the same name as the article file, except for the 
prefix and the proper file extension.

Commit and push to your previously created branch.

## Step 3: Open a pull request

Create a pull request from your branch against the `master` branch.
Therefore, please click on "New pull request" and follow the instructions 
in the already pre-filled description of the pull request.

## Step 4: Review

In order to be merged, the pull request requires two approvals from the 
review team.

Reviewers can add comments in the pull request's comment thread if
something should be changed.  When editing your article, simply commit
and push the changes to your branch; they are automatically added to
the pull request.

## Step 5: Image

Once the article itself is approved, the artist(s) add their images to
the pull request by placing it in the `images` directory on the
article's branch with the same name as the article file, except for
the proper file extension.  If there already is an image, it can be
savely replaced.

## Step 6: Image Review

See step 4.

## Step 7: Merge or Archive

If everything is ok, the pull request can be merged.  Be sure to
choose the `Squash and Merge` merge option.

If the plenum decided to archive the article, the pull request is
closed without merging.
