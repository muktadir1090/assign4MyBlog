# assign4MyBlog
# Personal Blog Website
# Personal Blog

## Description
This is a personal blog application designed for marketing students to showcase their thoughts and experiences. The blog features a form to input blog posts, localStorage persistence for storing entries, and a light/dark mode toggle to customize the appearance.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/personal-blog.git

2.	Open the project folder:

cd personal-blog


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
3.	Open the index.html file in your browser.

No additional installations are required since this is a front-end application using localStorage for data persistence.

## Screenshots
![alt text](<Screenshot 2024-10-07 at 12.42.00 AM.png>)
![alt text](<Screenshot 2024-10-07 at 12.54.38 AM.png>)
![alt text](<Screenshot 2024-10-07 at 12.52.33 AM.png>)
![alt text](<Screenshot 2024-10-07 at 12.53.16 AM.png>)


## Usage

	1.	Landing Page: On loading the application, you will be presented with a form to create a new blog post. The form requires a username, blog title, and content.
	2.	Submit Post: After filling out the form and submitting, the blog data will be saved to localStorage, and you will be redirected to the posts page.
	3.	Posts Page: This page displays a list of blog posts saved in localStorage, including the username, title, and content of each post.
	4.	Form Validation: If you attempt to submit the form without completing all fields, an error message will prompt you to fill in the missing information.
	5.	Light/Dark Mode: A toggle button allows switching between light and dark modes for customizing the appearance of the blog.
	6.	Back Button: On the posts page, you can click the “Back” button to return to the landing page and add more blog entries.

## Features

	•	Form for Blog Posts: Inputs for username, title, and blog content with validation.
	•	LocalStorage: Blog posts are stored in the browser’s localStorage for persistence.
	•	Light/Dark Mode Toggle: Users can switch between light and dark themes.
	•	Post Listing: The posts page displays all saved blog posts with the author, title, and content.
	•	Responsive Design: The app is designed to work across different devices and screen sizes.
	•	Footer with Portfolio Link: A link to the developer’s portfolio is included in the footer.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Contributions are welcome for improving features, bug fixes, or adding new functionality.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
