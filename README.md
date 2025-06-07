# Introduction

In this section you will practice React basics while making sure you follow the team's standards

Some basic points to keep in mind:

- Make sure to work on each feature you add in it's own branch. The naming convention for branches is feature/X for features, bugfix/X for bugfixes.
- Keep your files organized according to this file structure:

  - components - Contains all of your components. Make sure to put the components logic and css in the same folder.
  - modules - Contains interfaces that are used across several places in your code (not props).
  - services - Contains logic that is usually connected to an external API / server endpoint call.
  - utils - Usually contains at least a utils file and maybe others. Used to save utility functions that are used all over the code (Think about things like converting a string to a date, converting camelCase to snake_case, etc...).
  - config - Contains all configuration files. These are different than the things you put in .env. If you aren't sure about the difference read about it online and consult with the person responsible for this part in your training.

- Known libraries we use:
  - vite - Used for building our react projects.
  - MUI - For good looking, out of the box components.
  - tailwind - Not used with MUI, but makes working with css easier.
  - jotai - For state management (Doesn't mean you never use useState or Context).
  - react-leaflet - For displaying maps.
  - leaflet-geoman - For displaying shapes on the map and interacting with them.
  - playwright - for e2e tests
  - react-toastify - For displaying toast notifications.

While these are the team's standards, by no means should you treat them as absolute rules.</br> Doubt everything and if you think there is room for improvement make sure you speak up!
A fresh perspective can always help to find flaws.

# Things to use during this chapter

- [northwind-rest-api](https://www.npmjs.com/package/northwind-rest-api) - This npm package will provide the workers information.
- [api ninjas](https://api-ninjas.com/) - This is a free API that you will need to use.
