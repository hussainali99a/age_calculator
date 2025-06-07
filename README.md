# Frontend Mentor - Age calculator app

(Note: Replace the placeholder image URL above with an actual screenshot of your deployed app when you're ready.)

Welcome! 👋
Thanks for checking out my solution to the Age calculator app challenge on Frontend Mentor!

Frontend Mentor challenges help you improve your coding skills by building realistic projects.

The challenge
Users should be able to:

View an age in years, months, and days after submitting a valid date through the form.

Receive validation errors if:

Any field is empty when the form is submitted.

The day number is not between 1-31.

The month number is not between 1-12.

The date is in the future.

The date is invalid, e.g. 31/04/1991 (there are 30 days in April).

View the optimal layout for the interface depending on their device's screen size.

See hover and focus states for all interactive elements on the page.

Bonus: See the age numbers animate to their final number when the form is submitted.

My Solution
Features
My solution includes the following features:

Input Fields: Separate input fields for day, month, and year.

Comprehensive Date Validation:

Checks for empty fields.

Validates day (1-31), month (1-12), and year ranges.

Ensures the entered date is not in the future (relative to the current date).

Validates for specific invalid dates (e.g., 31/04, February 29th in a non-leap year) by checking Date object integrity.

Displays clear, context-specific error messages dynamically below the corresponding input fields.

Highlights invalid input fields with a distinct red border and label text for immediate visual feedback.

Accurate Age Calculation: Precisely calculates the age in years, months, and days based on the valid input date and the current date.

Animated Results: The calculated age numbers (years, months, days) animate smoothly from -- (or 0) to their final computed values upon successful form submission, providing an engaging user experience.

Fully Responsive Design: The layout is designed to be fully responsive, adapting seamlessly to various screen sizes, from mobile phones to larger desktop displays, ensuring optimal viewing and usability across devices.

Interactive Elements: All interactive elements, such as input fields and the submit button, include distinct hover and focus states, enhancing user interaction and accessibility.

Technologies Used
HTML5: Provides the foundational structure and semantic markup for the web application.

CSS3 (Tailwind CSS): Utilized for rapid and efficient styling, including responsive design utilities. The Tailwind CSS CDN is directly integrated for simplicity.

JavaScript: Powers the core logic of the application, handling user input, implementing robust validation rules, performing the age calculation, and managing the number animation for results.

Setup and Usage
To get a copy of this project up and running on your local machine, follow these simple steps:

Save the file: Copy the entire HTML code (from the age-calculator-app immersive provided previously) and save it as index.html in a folder on your computer.

Open in browser: Navigate to the index.html file in your file explorer and open it directly with your preferred web browser (e.g., Chrome, Firefox, Edge). No server setup is required for this client-side application.

How to Use
Open the index.html file in your web browser.

Enter the Day, Month, and Year of the birth date you wish to calculate in the respective input fields.

Click the purple circular arrow button to trigger the age calculation.

If the date entered is valid, your age will be displayed in years, months, and days in the results section, accompanied by a smooth counting animation.

If any validation errors occur (e.g., empty fields, invalid date, future date), corresponding error messages will appear below the problematic input fields, and the input areas will be highlighted in red to indicate an issue.

Project Structure
.
├── index.html          # Main application file (contains all HTML, CSS, and JavaScript)
└── README.md           # This readme file

Styling
The application features a clean, modern, and user-friendly design, with a strong emphasis on visual appeal and usability.

Font: 'Inter', sans-serif, providing a modern and highly readable typeface.

Color Palette:

Background: Light grey (hsl(0, 0%, 94%))

Card Background: Pure white (hsl(0, 0%, 100%))

Label Text: Smokey grey (hsl(0, 1%, 44%))

Input Text: Off black (hsl(0, 0%, 8%))

Primary Accent (Purple): hsl(259, 100%, 65%) (Used for the button, animated numbers, and input focus state)

Error Indicators (Light Red): hsl(0, 100%, 67%)

Responsiveness: Extensively uses Tailwind CSS's responsive utility classes (md:) to ensure the layout dynamically adjusts and provides an optimal user experience across various screen sizes, from mobile devices to large desktop monitors.

Future Improvements (Potential Enhancements)
Accessibility: Further enhance keyboard navigation support and ARIA attributes for users relying on assistive technologies.

Date Picker Integration: Implement a graphical date picker (e.g., a custom one or a lightweight library) to make date selection more intuitive and prevent common input errors.

Clear Button: Add a dedicated "Clear" button to easily reset all input fields and results.

Unit Testing: Develop comprehensive unit tests for the JavaScript validation and age calculation logic to ensure robustness and maintainability.

Modularity: For larger applications, refactor the JavaScript into more modular functions or components, potentially using a framework if expanding beyond a single HTML file.

Building your project (General Guidance)
Feel free to use any workflow that you feel comfortable with. Below is a suggested process, but do not feel like you need to follow these steps:

Initialize your project as a public repository on GitHub. Creating a repo will make it easier to share your code with the community if you need help. If you're not sure how to do this, have a read-through of this Try Git resource.

Configure your repository to publish your code to a web address. This will also be useful if you need some help during a challenge as you can share the URL for your project with your repo URL. There are a number of ways to do this, and we provide some recommendations below.

Look through the designs to start planning out how you'll tackle the project. This step is crucial to help you think ahead for CSS classes to create reusable styles.

Before adding any styles, structure your content with HTML. Writing your HTML first can help focus your attention on creating well-structured content.

Write out the base styles for your project, including general content styles, such as font-family and font-size.

Start adding styles to the top of the page and work down. Only move on to the next section once you're happy you've completed the area you're working on.

Deploying your project (General Guidance)
As mentioned above, there are many ways to host your project for free. Our recommended hosts are:

GitHub Pages

Vercel

Netlify

You can host your site using one of these solutions or any of our other trusted providers. Read more about our recommended and trusted hosts.

Submitting your solution (General Guidance)
Submit your solution on the platform for the rest of the community to see. Follow our "Complete guide to submitting solutions" for tips on how to do this.

Remember, if you're looking for feedback on your solution, be sure to ask questions when submitting it. The more specific and detailed you are with your questions, the higher the chance you'll get valuable feedback from the community.

Sharing your solution (General Guidance)
There are multiple places you can share your solution:

Share your solution page in the #finished-projects channel of the community.

Tweet @frontendmentor and mention @frontendmentor, including the repo and live URLs in the tweet. We'd love to take a look at what you've built and help share it around.

Share your solution on other social channels like LinkedIn.

Blog about your experience building your project. Writing about your workflow, technical choices, and talking through your code is a brilliant way to reinforce what you've learned. Great platforms to write on are dev.to, Hashnode, and CodeNewbie.

We provide templates to help you share your solution once you've submitted it on the platform. Please do edit them and include specific questions when you're looking for feedback.

The more specific you are with your questions the more likely it is that another member of the community will give you feedback.

Got feedback for us? (General Guidance)
We love receiving feedback! We're always looking to improve our challenges and our platform. So if you have anything you'd like to mention, please email hi@frontendmentor.io.

This challenge is completely free. Please share it with anyone who will find it useful for practice.

Have fun building! 🚀
