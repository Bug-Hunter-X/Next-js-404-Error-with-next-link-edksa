# Next.js 404 Error with next/link

This repository demonstrates a common Next.js issue where a 404 error is thrown when navigating between pages using the `next/link` component, even though the destination page exists in the `pages` directory.

## Bug Description
The application uses `next/link` to navigate to an 'about' page. However, it produces a 404 error. The `about.js` file is present in the `pages` directory. The code for the home page (index.js) and about page (about.js) can be found in the `bug.js` file.

## Bug Solution
The solution is provided in the `bugSolution.js` file. The solution involves ensuring that the file `about.js` is correctly placed inside the `pages` directory, and that the path in the `next/link` component is specified correctly.