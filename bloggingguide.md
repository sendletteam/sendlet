# Comprehensive Guide: Blogging with Sendlet's HTML Template

# Introduction:
Welcome to the complete guide on using Sendlet's minimalist HTML blogging template. This guide will walk you through setting up your profile, writing blog posts, and customizing the appearance of your blog.

# 1. Setup Your Blog Title:
In the <head> section, locate the <title> tag. Replace [your name] with your actual name or desired blog name.


```
<title>Sendlet - [your name]'s Blog</title>
```

# 2. Customize Your Profile:
Within the <body>, you'll find the #profile-section. Here's how you can add your details:

Blogger Name: Replace Blogger Name with your actual name.
Sendlet user since: Replace [year] with the year you started using Sendlet.
Pronouns: Replace [your/pronouns] to display your pronouns.
Blogging about: Mention your blog's primary topics.
Fan of: Share a few of your favorite things.

```
<section id="profile-section">
    ...
    <h2>Blogger Name</h2>
    <p>Sendlet user since [year]<br>Pronouns are [your/pronouns]<br> Blogging about [topic]<br> Fan of [your favorite things]</p>
    ...
</section>
```

# 3. Writing Blog Posts:
To add a new blog post:

Post Title: Replace Your blog post title with your actual post title.
Date: Replace [date written] with the date of your post.
Content: Replace the "Lorem ipsum..." text with your blog post content.
Every time you want to add a new blog post, simply copy and paste the <article> template and follow the above instructions:

```
<article>
    <h2>Your blog post title</h2>
    <h4>Written on [date written]</h4>
    <p>Your blog content here...</p>
</article>
```

# 4. Customizing Appearance:
In the <style> section, you can make adjustments to the look and feel of your blog. Here are some components you might want to tweak:

Fonts: The template uses 'Poppins' from Google Fonts. You can change this by modifying the link in the <link> tag at the top.
Colors: Throughout the CSS, there are hex color codes (like #9003fc). Adjust these values to change the color scheme.
Spacing & Size: Modify properties like margin, padding, font-size etc. to adjust spacing and sizes.

# 5. Engage with your audience:
There's a nifty "Follow this blogger" button using the checkbox hack. When a user clicks on this, the button's appearance changes, simulating a "following" state.

# 6. Publishing Your Sendlet Blog with GitHub Pages:

One of the most streamlined ways to bring your Sendlet blog to life on the internet is by utilizing GitHub Pages. This free platform by GitHub allows users to host static websites directly from their GitHub repositories. Below is a step-by-step guide to get your Sendlet blog online:

Sign in to your GitHub account. If you don't have one, registration is straightforward and free.
Once logged in, click on the '+' icon at the top right corner and choose "New repository".
Name your repository. If you want a custom domain like yourname.github.io, name the repository exactly that. Otherwise, you can choose any name.
Make sure to initialize it with a README.
Click 'Create Repository'.

Once your repository is created, click on the 'Add file' button and select 'Upload files'.
Drag and drop your Sendlet HTML file (and any associated assets like images, if any) into the window.
Add a description for your changes, something like "Initial Sendlet blog upload".
Click 'Commit changes'.

In your repository, navigate to the 'Settings' tab.
Scroll down to the 'GitHub Pages' section.
Under 'Source', select the branch you want to deploy (usually main or master).
The page will refresh, and you should now see a notification that your site is published along with its link.

Click on the provided link in the GitHub Pages section or directly navigate to https://[yourusername].github.io/[repositoryname] in your browser to view your blog.

Remember, every time you make an update to your blog's HTML file on GitHub, GitHub Pages will automatically update your live blog within a few minutes.

If you wish to use a custom domain instead of the default github.io, you can follow GitHub's official guide on configuring a custom domain for your GitHub Pages site.

# 7. Final Words:
Always remember to save your changes and preview them in a browser to ensure everything looks as expected before deploying your blog on GitHub Pages. Enjoy blogging with Sendlet! 🎉
