<style global lang="sass">

  *
    box-sizing: border-box
    margin: 0px
    padding: 0px
    text-align: left
    font-weight: inherit
    border-radius: 0px
    // eliminate focus glow on :active on some browsers
  *:focus
    outline: none
    box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px 0px inset

  div
    position: relative

  // todo: delete this after putting into components
  button, input[type="button"], input
    border: none
    background: transparent
    font-family: var(--font-family-primary)
    &:focus
      outline: none

  a, a > em
    text-decoration: none

  a > em
    font-style: normal

  a:hover > em
    text-decoration: underline


  a, a:hover, a:visited, a:active
    color: var(--black)


  html, body
    min-width: var(--breakpoint-min)
    width: 100%
    height: 100%

  ul, ol
    list-style-type: none

  ul[unstyled], ol[unstyled]
    list-style-type: none !important
    li
      margin-left: 0px !important

  table
    border-spacing: 0
    border-collapse: collapse
    td, th
      vertical-align: top


  details summary::-webkit-details-marker
    display: none
    font-size: 0px

  a, b, i, strong, em
    font-weight: inherit
    text-decoration: inherit

  hr
    border-top: 1px solid var(--lightest-gray)



</style>