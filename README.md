# assign4MyBlog
# Personal Blog Website

## Project Overview

This project involves creating a two-page website where users can input and view blog posts. The application includes a content form for submitting posts, dynamically renders blog posts, and provides a light/dark mode toggle. This challenge is a great way to gain hands-on experience with JavaScript, the Document Object Model (DOM), and web development concepts.

## User Story

```md
AS A marketing student,
I WANT a personal blog
SO THAT I can showcase my thoughts and experiences.
GIVEN a personal blog
WHEN I load the app,
THEN I am presented with the landing page containing a form with labels and inputs for username, blog title, and blog content.
WHEN I submit the form,
THEN blog post data is stored to localStorage.
WHEN the form submits,
THEN I am redirected to the posts page.
WHEN I try to submit a form without a username, title, or content,
THEN I am presented with a message that prompts me to complete the form.
WHEN I view the posts page,
THEN I am presented with a header, a light mode/dark mode toggle, and a "Back" button.
WHEN I click the light mode/dark mode toggle,
THEN the page content's styles update to reflect the selection.
WHEN I click the "Back" button,
THEN I am redirected back to the landing page where I can input more blog entries.
WHEN I view the main content,
THEN I am presented with a list of blog posts that are pulled from localStorage.
WHEN I view localStorage,
THEN I am presented with a JSON array of blog post objects, each including the post author's username, title of the post, and post's content.
WHEN I take a closer look at a single blog entry in the list,
THEN I can see the title, the content, and the author of the post.
WHEN I view the footer,
THEN I am presented with a link to the developer's portfolio.


File Structure
my-blog
├── assets
│   ├── css
│   │   ├── blog.css
│   │   ├── form.css
│   │   └── styles.css
│   └── js
│       ├── blog.js
│       ├── form.js
│       └── logic.js
├── index.html
├── blog.html
└── README.md
3.	Open index.html in Your Web Browser
This will display the landing page where you can input new blog entries.
	4.	Use the Form
Fill out the form with a username, blog title, and content. Upon submission, the data will be saved to localStorage and you will be redirected to blog.html.
	5.	View and Manage Blog Posts
On the blog.html page, you can view the list of blog posts, toggle between light and dark modes, and use the “Back” button to return to the landing page.

Technologies Used

	•	HTML
	•	CSS
	•	JavaScript

Contributing

Feel free to fork the repository and submit pull requests with improvements or bug fixes. Ensure you follow the existing code style and conventions.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Contact

For any questions or suggestions, please contact Your Name.
