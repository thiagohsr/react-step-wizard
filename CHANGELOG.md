# Changelog
All notable changes to this project will be documented in this file.

### [4.4.0]
• Added navigation feature! 🎉

> Dev Changes
• Added Jest for unit/snapshot testing
• Upgraded to Babel 7

### [4.3.1]
• Updated component to change step `onhashchange` when using browser back/forward buttons - (applicable only when `isHashEnabled` is `true`)

### [4.3.0]
• Added `hashKey` for persisting step in URL
• Removed `active` prop for child components - use `initialStep` instead

### [4.2.0]
• Added `onStepChange` callback for when step changes

### [4.1.2]
• Fix for IE support

### [4.1.1]
> Dev Changes
    • Added PropTypes for development

### [4.1.0]
• Added `isLazyMount` prop for dynamically mounting steps

> Dev Changes
    • Added webpack-dev-server to example for convenience

### [4.0.0] \*Breaking Changes\*
• Removed `Step` component. It wasn't necessary
• Made `StepWizard` the default export

> Dev Changes
    • Updated eslint rules

### [3.0.1]
> Dev Changes
• clean up dev dependencies
• Update to example demo

### [3.0.0] \*Potentially Breaking Changes\*
• Added `isActive` prop and `initialStep`
• Remove example/ from npm

> Dev Changes
• Updated webpack configs
• Added airbnb eslint rules.
• Updated components for eslint and es6 standards

### [2.0.0]
• Use style-loader to handle CSS