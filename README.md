# LearnHub --- E-Learning Platform

LearnHub is a responsive e-learning dashboard built with HTML and CSS.
It presents a learning portal where students can explore courses, view
learning progress, watch course content, and see upcoming activities.

## Features

-   Responsive layout for desktop, tablet, and mobile screens
-   LearnHub header and navigation
-   Course search field
-   Hero section with an Explore Courses link
-   Course cards and category filters (as defined in the HTML)
-   Learning progress indicators
-   Embedded video section
-   Sidebar areas for upcoming activities, recent courses, and
    achievements
-   Footer with resource and social links
-   Font Awesome icons and Google Fonts

## Project Structure

``` text
project/
├── index.html
├── my.jpeg        # Profile image referenced by index.html
└── README.md
```

Keep `my.jpeg` in the same folder as `index.html`, or update the image
path in the HTML to match your file.

## Run Locally

1.  Download or clone the project.
2.  Make sure `index.html` and `my.jpeg` are in the same folder.
3.  Open `index.html` in a web browser.

For a local development server, you can use the VS Code **Live Server**
extension and select **Open with Live Server**.

## Technologies Used

-   HTML5
-   CSS3
-   Google Fonts: Poppins and Open Sans
-   Font Awesome 6.4.0
-   External course/video links

## Configuration

Some links and assets are currently hard-coded in `index.html`:

-   Profile image: `my.jpeg`
-   Course links: Udemy URLs
-   Explore Courses link: YouTube programming search
-   Font Awesome and Google Fonts: loaded from external CDNs

Change these URLs and asset paths in `index.html` to customize the
dashboard.

## Important Notes

-   This project is currently a **front-end website**. The supplied HTML
    does not itself provide user authentication, a database, persistent
    course progress, or a backend API.
-   The search box and course filters require JavaScript to perform
    actual filtering/searching if that behavior is not implemented
    elsewhere in the project.
-   Some websites may block embedding in an iframe. If an embedded
    course page does not load, open the course using a normal link
    instead.
-   External fonts and icons require an internet connection.

## Possible Improvements

-   Add JavaScript for working course search and category filters
-   Add login/signup and user profiles
-   Connect a backend and database to store users, courses, and progress
-   Add course enrollment and lesson tracking
-   Improve accessibility with keyboard navigation and clear focus
    states

## License

No license is specified. Add a `LICENSE` file before distributing or
reusing the project if you want to define its usage terms.
