# Epic Stack Example with Framer Motion

This demonstrates how to use Framer Motion with the Epic Stack. Easiest way to
explore this is to check the commit history to see what changed from the `init`
commit.

Pretty much:

1. Install `framer-motion`
2. Add a client hint for `prefers-reduced-motion`
3. Use framer motion with `reducedMotion` to respect user preferences, even on
   the server render.
