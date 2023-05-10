# Phase// Customizations

P// has added a lot of additional functionality to the Admin UI. Those are cordoned off as much as possible from the main Admin UI repo to keep them from being clobbered by various updates to the main Admin UI repo. The list below is the area of customizations.

- `PageNav.tsx`
  - Extensions nav group imported from the `phaseII/navigation` folder
- Translations
  - Files have to live in the `/public/resources/en` folder
  - `orgs.json`
  - `styles.json`
  - Ensure these are listed in the `i18n.ts` file as one of the `ns` options
- Orgs
  - This folder contains all the Orgs UI. It exists mostly independent of other code, but does import components from the `ui-shared` and the `src/components` folder.
- Custom
  - This folder contains all the Custom Styles UI. It exists mostly independent of other code, but does import components from the `ui-shared` and the `src/components` folder.
