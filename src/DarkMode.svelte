<style>

  :global(body) {

      --background-light: var(--white);
      --background-dark: var(--black);
      --foreground-light: var(--black);
      --foreground-dark: var(--lightest-gray);
  }
    /* general overrides */
  @media (prefers-color-scheme: dark) {
    :global(a), :global(a:hover), :global(a:visited), :global(a:active) {
      color: var(--foreground-dark); } }


</style>