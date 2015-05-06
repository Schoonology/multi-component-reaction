# MCR: Multi-Component Reaction

In chemistry, an MCR or multi-component reaction is when three or more
compounds _react_ to form a single product. What a fine name for a collection
of React components.

## Goals

* Easy stylability - MCR uses BEM for class names and LESS to generate starting
  styles. This makes the specificity of the starting styles easy to match, so
  their easy to override.
* Feel like React - Core React attribute names like `value`, `defaultValue`,
  `onChange`, etc. are used wherever possible to give the feeling they're
  natives to the React environment.
* Maximum forkability - In the end, these can't serve everyone's needs
  perfectly, so the repo aims to be optimixed for maximum fork-and-tweak
  capability.

## Installation

```
npm install --save mcr
```

## Alternatives

[React Components](components) is a fantastic resource for finding alternatives
to MCR. For example, [this search](dropdown) will give you a bunch of
replacement dropdown menus.

[components]: http://react-components.com/
[dropdown]: http://react-components.com/search/dropdown
