## Getting Started
- Use src options and create folders and page.tsx structure

## Links
- Use the builtin Link component `import Link from 'next/link`
- <Link href="/performance">Performance</Link>

## Layout
- Common elements are added here
- It is a global layout
- Other pages are displayed inside of the layout component

## Components
- Used for reusable components
- src/app has all the page.tsx files 
- rather create it in src
- leave the routes in app

## Image
 - The built in Image is used to make sure that content is not jumping around and that you dont get layout shifting
 - If you are using imported image, the dimensions are taken from the imported image
 - if online hosted you can code in the dimensions.
 - the fill prop is used to exapnd and fill up the parent component

 ## Reusable Presentation Components
- This would be something like a hero component
- this is where we pass props like ImgData, imgAlt and title down to each page
- The use the component and pass the props into it inside each of the pages

## Deploying
- run npx vercel
- Use ./ for the directory where code is located