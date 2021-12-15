# playjs-nuxt-template

A simple Nuxt 2.15.7 project scaffolded using the CLI tool and adapted to suit play.js development.

This template uses Tailwind.

Some caveats:

- You will not be able to auto-format with prettier. Instead, run the `format` script to do so manually.
    - A print width of 54 characters is generally safe for iPhones if the smallest font size is used and line numbers are disabled in IDE settings.
- Your scripts do not run within a shell environment, so shell commands won't work. 
    - The `onchange` package to watch file/directory changes will also refuse to work properly.
- Unit testing frameworks generally work, but UI/E2E frameworks will not.
    
Obviously, caveats extend to more than the above list. Regardless, a basic workflow works well. Develop away!