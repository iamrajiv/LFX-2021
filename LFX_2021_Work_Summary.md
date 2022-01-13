<div align="center">
<img src="assets/lfx-2021-1.svg" height= "auto" width="200" />
<br />
<img src="assets/lfx-2021-2.webp" height= "auto" width="200" />
<br />
<h1>moja global</h1>
<h3>
Cloud native measurement, reporting and validation of carbon emissions
<br />
Work Summary
</h3>
</div>

### Prior Work:

- [x] [#16](https://github.com/moja-global/FLINT-UI/pull/16): Added installation guidelines in README on how to set up and run FLINT UI locally.
- [x] [#32](https://github.com/moja-global/FLINT-UI/pull/32): Added Storybook support to manage components, stories, and documentation.
- [x] [#66](https://github.com/moja-global/FLINT-UI/pull/66): Integrated and deployed Storybook on Chromatic.

### Week 1 (September 3 - September 9, 2021)

- Weekly meeting schedule agreed.
- Getting familiar with FLINT UI codebase.
- Making Design doc for FLINT UI.

### Week 2 (September 10 - September 16, 2021)

- [x] [#70](https://github.com/moja-global/FLINT-UI/pull/70): Fixed Irregular card size in FLINT UI dashboard.
- [x] [#72](https://github.com/moja-global/FLINT-UI/pull/72): Migrated FLINT UI to Yarn package manager.
- [x] [#74](https://github.com/moja-global/FLINT-UI/pull/74): Fixed output simulation table value bug by updating it to read-only mode.
- [x] [moja-global/FLINT.Example#25](https://github.com/moja-global/FLINT.Example/pull/25): Added GitHub action pipeline to build and publish Flint.Example Docker image to GitHub container registry.

### Week 3 (September 17 - September 23, 2021)

- [x] [#78](https://github.com/moja-global/FLINT-UI/pull/78): Improved toast notifications of Help, Point, RothC Specification, and Version by adding more meaningful messages.

- [x] [#80](https://github.com/moja-global/FLINT-UI/pull/80): Added stories for the button, card, and footer component in Storybook.

### Week 4 (September 24 - September 30, 2021)

- [x] [#87](https://github.com/moja-global/FLINT-UI/pull/87): Ignored irrelevant paths from Chromatic Action so now it will be triggered only when there is a file change in `flint.ui/.storybook/**`, and `flint.ui/src/stories/**`. Also, added Dependabot to update Flint.Cloud submodule means Dependabot will make a PR automatically whenever new changes are pushed to Flint.Cloud repository. This will help the submodule in FLINT UI to be consistent with the main Flint.Cloud repository.

### Week 5 (October 1 - October 7, 2021)

- [x] [#91](https://github.com/moja-global/FLINT-UI/pull/91): Truncated Point and RothC output up to five significant figures using `toPrecision()` method.

### Week 6 (October 8 - October 14, 2021)

- [x] [#92](https://github.com/moja-global/FLINT-UI/pull/92): Added Continuous Integration for FLINT UI like installing dependencies, linting the code, building the Vue app, and building the Storybook whenever there is PR or Push to the master branch of the repository.

### Week 7 (October 15 - October 21, 2021)

- [x] [#96](https://github.com/moja-global/FLINT-UI/pull/96): Formatted step date column from ISO 8601 date to `YYYY-MM-DD` form. JavaScript supports ISO 8601 date format by default i.e. `YYYY-MM-DDTHH:mm:ss.sssZ` but when we are running a simulation for hundreds of years then hours, minutes, and seconds don't matter very much so we only care about the date.

### Week 8 (October 22 - October 28, 2021)

- [x] [#102](https://github.com/moja-global/FLINT-UI/pull/102): Added `vue-tour` support for FLINT UI . Vue Tour is a lightweight, simple, and customizable guided tour plugin for use with Vue.js. It provides a quick and easy way to guide your users through your application.

### Week 9 (October 29 - November 4, 2021)

- [x] [moja-global/FLINT.Cloud#46](https://github.com/moja-global/FLINT.Cloud/pull/46): Removed top-level `rest_api_*` folders i.e. `rest_api_flint.example/**` and `rest_api_gcbm/**`.

### Week 10 (November 5 - November 11, 2021)

- [x] [#136](https://github.com/moja-global/FLINT-UI/pull/136): Added `Alerts`, `Divider`, `Progress`, and`PopupConfirm` component and stories in FLINT UI.

### Week 11 (November 12 - November 18, 2021)

- [x] [moja-global/FLINT.Cloud#48](https://github.com/moja-global/FLINT.Cloud/pull/48): Added Terraform script to generate globally unique Google Cloud Storage bucket name.

### Week 12 (November 19 - November 25, 2021)

- [x] [moja-global/FLINT.Cloud#50](https://github.com/moja-global/FLINT.Cloud/pull/50): Moved dictionary inserts to its definition.
