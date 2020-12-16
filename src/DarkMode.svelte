<style global lang="sass">

  \:root

    --background-light: var(--white)
    --background-dark: var(--black)
    --foreground-light: var(--black)
    --foreground-dark: var(--lightest-gray)

  // general overrids
  @media (prefers-color-scheme: dark)
    a, a:hover, a:visited, a:active
      color: var(--foreground-dark)

</style>