// CSS Types Used:

1. Inline CSS:- Used on the `<body>` tag to set the background color.  
Example:  
<body style="background-color: #1c1c3c;">

2. Internal CSS:- Placed inside the `<head>` section to style headings and hover effect on contact links.  
Example:  
h1, h3 { font-family: 'Segoe UI', sans-serif; color: #fff; }

3. External CSS:- Most of the styling is written in `style.css`, linked in the HTML.  
Includes layout, colors, buttons, cards, spacing, lists, and responsiveness.


// CSS Selectors Used:

1. Element selectors:- Used for styling default HTML tags like `body`, `p`, `ul`, `li`, `h1`, `img`, etc.

2. Class selectors:- Used for custom reusable sections like `.card`, `.btn`, `.contact`, `.skills`, `.hobbies`, etc.

3. ID selector:- Used for targeting a unique element — the profile image.  
Example: `#image`

4. Group selector:- Used to apply common styles to multiple elements at once.  
Example: `h1, h3`

5. Descendant selector:- Used to target elements inside a class.  
Example: `.contact a[href]` (targets only links inside the contact section)

6. Attribute selector:- Used to style anchor tags with `href`.  
Example: `a[href]` for all hyperlinks

7. Hover effects:- Used on buttons, hobbies list items, and contact links to make the UI interactive.
