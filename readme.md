# Front End Mentor template

This is a template for solving single page FrontEndMentor challenges.  

It uses:
- Yarn for package management https://yarnpkg.com/
- Parcel https://parceljs.org/
- Pug for HTML templates https://pugjs.org/
- TailwindCSS  for css https://tailwindcss.com/


## Starting a new project
Follow these steps to start a new project

- Clone the template repository
- Open terminal in the project root
- Delete the `.git` directory to detach from the template Git repo.
   ```shell
  rm -rf .git
  ```
- Install all the required packages
   ```shell
  yarn install
  ```


## Working on the solution

- Run parcel local server  
  Parcel automatically provides Live Reload. Every time you change the files,
  browser automatically reloads the page.
   ```shell
  yarn parcel src/index.pug
  ```
- `src/index.pug` in the main file where you put your solution
- `src/styles/index.scss` - is the place for styles
- `src/assets` is the place for images
