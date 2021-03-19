# Thinking with React

Step 1. Draw boxes around each component (and subcomponents).

Step 2. Build a static Website

dont use state when building your static site.

You can build it from top to bottom or bottom to top.

bottom up would mean building tests as you build the site.

top down would be building components highter up in the hierarchy


there are two types of model data. STate nd props

props is short for properties.

props get passed to the component(similar to function parameters)

sstate is managed within the component (similar to variables inside a function)

both state and prop represent the rendered values.

1. Is it passed in from a parent via props? If so, it probably isn’t state.

2. Does it remain unchanged over time? If so, it probably isn’t state.

3. Can you compute it based on any other state or props in your component? If so, it isn’t state.