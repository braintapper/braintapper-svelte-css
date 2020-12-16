<style global lang="sass">



  // box shadow

  [shadow="vertical"], [shadow="top"]
    box-shadow: 0px 2px 5px 0px var(--box-shadow)
  [shadow="bottom"]
    box-shadow: 0px 0px 2px 5px var(--box-shadow)
  [shadow="right"], [shadow="horizontal"]
    box-shadow: 2px 0px 5px 0px var(--box-shadow)
  [shadow="left"]
    box-shadow: -2px 0px 5px 0px var(--box-shadow)

  // overlay
  [type="overlay"]
    display: none
    height: 100%
    width: 100%
    position: fixed
    z-index: var(--z-index-overlay)
    top: 0
    left: 0
    background-color: var(--overlay)
    opacity: var(--overlay-opacity)
    &[clear]
      background-color: transparent
    &[open="true"]
      display: block



  // visibility
  [show]
    display: block
  [show="false"], [hide="true"], .hidden
    display: none
  [show="false!"], [hide="true!"]
    display: none !important

  [show="true!"]
    display: block !important

  // horizontal and vertical centering

  [c*="v"]
    position: relative
    top: 50%
    transform: translateY(-50%)
    /* prefixes needed for cross-browser support */
    -ms-transform: translateY(-50%)
    -webkit-transform: translateY(-50%)

  [c*="h"]
    margin: 0 auto
    //left: 50%
    //transform: translateX(-50%)
    /* prefixes needed for cross-browser support */
    //-ms-transform: translateX(-50%)
    //-webkit-transform: translateX(-50%)




  // todo: add more configs here
  [scroll]
    overflow: auto
  [scroll-x]
    overflow-x: scroll
  [scroll-y]
    overflow: scroll
  [noscroll]
    overflow: hidden


  // SIZING

  $size-list: 8 10 12 24 36 40 48 50 60 64 72 80 96 100 120 128 140 150 200 240 300

  @each $size in $size-list
    [w="#{$size}"]
      width: #{$size}
    [w="#{$size}!"]
      width: #{$size} !important
    [h="#{$size}"]
      height: #{$size}
    [h="#{$size}!"]
      height: #{$size} !important



  $percent-list: "10%" "11.1%" "12.5%" "14.3%" "16.7%" "20%" "25%" "33.3%" "50%" "100%"

  @each $percent in $percent-list
    [w="#{$percent}%"]
      width: #{$percent}
    [w="#{$percent}%!"]
      width: #{$percent} !important
    [h="#{$percent}%"]
      height: #{$percent}
    [h="#{$percent}%!"]
      height: #{$percent} !important

  [w="tenth"]
    width:  nth($percent-list,1)
  [w="ninth"]
    width: nth($percent-list,2)
  [w="eighth"]
    width: nth($percent-list,3)
  [w="seventh"]
    width: nth($percent-list,4)
  [w="sixth"]
    width: nth($percent-list,5)
  [w="fifth"]
    width: nth($percent-list,6)
  [w="fourth"],[w="quarter"]
    width: nth($percent-list,7)
  [w="third"]
    width: nth($percent-list,8)
  [w="half"]
    width: nth($percent-list,9)
  [w="whole"], [w="full"]
    width: nth($percent-list,10)


  [w="tenth!"]
    width: nth($percent-list,1) !important
  [w="ninth!"]
    width:  nth($percent-list,2) !important
  [w="eighth!"]
    width: nth($percent-list,3) !important
  [w="seventh!"]
    width: nth($percent-list,4) !important
  [w="sixth!"]
    width: nth($percent-list,5) !important
  [w="fifth!"]
    width: nth($percent-list,6) !important
  [w="fourth!"],[w="quarter!"]
    width: nth($percent-list,7) !important
  [w="third!"]
    width: nth($percent-list,8) !important
  [w="half!"]
    width: nth($percent-list,9) !important
  [w="whole!"], [w="full!"]
    width: nth($percent-list,10) !important



  [h="tenth"]
    height:  nth($percent-list,1)
  [h="ninth"]
    height: nth($percent-list,2)
  [h="eighth"]
    height: nth($percent-list,3)
  [h="seventh"]
    height: nth($percent-list,4)
  [h="sixth"]
    height: nth($percent-list,5)
  [h="fifth"]
    height: nth($percent-list,6)
  [h="fourth"],[h="quarter"]
    height: nth($percent-list,7)
  [h="third"]
    height: nth($percent-list,8)
  [h="half"]
    height: nth($percent-list,9)
  [h="whole"], [h="full"]
    height: nth($percent-list,10)


  [h="tenth!"]
    height: nth($percent-list,1) !important
  [h="ninth!"]
    height:  nth($percent-list,2) !important
  [h="eighth!"]
    height: nth($percent-list,3) !important
  [h="seventh!"]
    height: nth($percent-list,4) !important
  [h="sixth!"]
    height: nth($percent-list,5) !important
  [h="fifth!"]
    height: nth($percent-list,6) !important
  [h="fourth!"],[h="quarter!"]
    height: nth($percent-list,7) !important
  [h="third!"]
    height: nth($percent-list,8) !important
  [h="half!"]
    height: nth($percent-list,9) !important
  [h="whole!"], [h="full!"]
    height: nth($percent-list,10) !important


  // sometimes you just want more space at the bottom of an element
  // since none of the elements have padding, these just add some more padding
  // depending on the element, it needs to be either padding or margin

  [padding-below-0]
    padding-bottom: var(--fine-spacing-0)
  [padding-below-xxs]
    padding-bottom: var(--fine-spacing-xxs)
  [padding-below-xs]
    padding-bottom: var(--fine-spacing-xs)
  [padding-below-s]
    padding-bottom: var(--fine-spacing-s)
  [padding-below-m]
    padding-bottom: var(--fine-spacing-m)
  [padding-below-l]
    padding-bottom: var(--fine-spacing-l)
  [padding-below-xl]
    padding-bottom: var(--fine-spacing-xl)
  [padding-below-xxl]
    padding-bottom: var(--fine-spacing-xxl)

  [padding-left-0]
    padding-left: var(--fine-spacing-0)
  [padding-left-xxs]
    padding-left: var(--fine-spacing-xxs)
  [padding-left-xs]
    padding-left: var(--fine-spacing-xs)
  [padding-left-s]
    padding-left: var(--fine-spacing-s)
  [padding-left-m]
    padding-left: var(--fine-spacing-m)
  [padding-left-l]
    padding-left: var(--fine-spacing-l)
  [padding-left-xl]
    padding-left: var(--fine-spacing-xl)
  [padding-left-xxl]
    padding-left: var(--fine-spacing-xxl)

  [margin-below-0]
    margin-bottom: var(--fine-spacing-0)
  [margin-below-xxs]
    margin-bottom: var(--fine-spacing-xxs)
  [margin-below-xs]
    margin-bottom: var(--fine-spacing-xs)
  [margin-below-s]
    margin-bottom: var(--fine-spacing-s)
  [margin-below-m]
    margin-bottom: var(--fine-spacing-m)
  [margin-below-l]
    margin-bottom: var(--fine-spacing-l)
  [margin-below-xl]
    margin-bottom: var(--fine-spacing-xl)
  [margin-below-xxl]
    margin-bottom: var(--fine-spacing-xxl)

  [margin-left-0]
    margin-left: var(--fine-spacing-0)
  [margin-left-xxs]
    margin-left: var(--fine-spacing-xxs)
  [margin-left-xs]
    margin-left: var(--fine-spacing-xs)
  [margin-left-s]
    margin-left: var(--fine-spacing-s)
  [margin-left-m]
    margin-left: var(--fine-spacing-m)
  [margin-left-l]
    margin-left: var(--fine-spacing-l)
  [margin-left-xl]
    margin-left: var(--fine-spacing-xl)
  [margin-left-xxl]
    margin-left: var(--fine-spacing-xxl)

  span[spacer]
    padding: 0px 4px
</style>