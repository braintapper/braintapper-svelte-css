<style>

:global([shadow="vertical"]), :global([shadow="top"]) {
  box-shadow: 0px 2px 5px 0px var(--box-shadow); }

:global([shadow="bottom"]) {
  box-shadow: 0px 0px 2px 5px var(--box-shadow); }

:global([shadow="right"]), :global([shadow="horizontal"]) {
  box-shadow: 2px 0px 5px 0px var(--box-shadow); }

:global([shadow="left"]) {
  box-shadow: -2px 0px 5px 0px var(--box-shadow); }

:global([type="overlay"]) {
  display: none;
  height: 100%;
  width: 100%;
  position: fixed;
  z-index: var(--z-index-overlay);
  top: 0;
  left: 0;
  background-color: var(--overlay);
  opacity: var(--overlay-opacity); }
  :global([type="overlay"][clear]) {
    background-color: transparent; }
  :global([type="overlay"][open="true"]) {
    display: block; }

:global([show]) {
  display: block; }

:global([show="false"]), :global([hide="true"]), :global(.hidden) {
  display: none; }

:global([show="false!"]), :global([hide="true!"]) {
  display: none !important; }

:global([show="true!"]) {
  display: block !important; }

:global([c*="v"]) {
  position: relative;
  top: 50%;
  transform: translateY(-50%);
  /* prefixes needed for cross-browser support */
  -ms-transform: translateY(-50%);
  -webkit-transform: translateY(-50%); }

:global([c*="h"]) {
  margin: 0 auto;
  /* prefixes needed for cross-browser support */ }

:global([scroll]) {
  overflow: auto; }

:global([scroll-x]) {
  overflow-x: scroll; }

:global([scroll-y]) {
  overflow: scroll; }

:global([noscroll]) {
  overflow: hidden; }

:global([w="8"]) {
  width: 8; }

:global([w="8!"]) {
  width: 8 !important; }

:global([h="8"]) {
  height: 8; }

:global([h="8!"]) {
  height: 8 !important; }

:global([w="10"]) {
  width: 10; }

:global([w="10!"]) {
  width: 10 !important; }

:global([h="10"]) {
  height: 10; }

:global([h="10!"]) {
  height: 10 !important; }

:global([w="12"]) {
  width: 12; }

:global([w="12!"]) {
  width: 12 !important; }

:global([h="12"]) {
  height: 12; }

:global([h="12!"]) {
  height: 12 !important; }

:global([w="24"]) {
  width: 24; }

:global([w="24!"]) {
  width: 24 !important; }

:global([h="24"]) {
  height: 24; }

:global([h="24!"]) {
  height: 24 !important; }

:global([w="36"]) {
  width: 36; }

:global([w="36!"]) {
  width: 36 !important; }

:global([h="36"]) {
  height: 36; }

:global([h="36!"]) {
  height: 36 !important; }

:global([w="40"]) {
  width: 40; }

:global([w="40!"]) {
  width: 40 !important; }

:global([h="40"]) {
  height: 40; }

:global([h="40!"]) {
  height: 40 !important; }

:global([w="48"]) {
  width: 48; }

:global([w="48!"]) {
  width: 48 !important; }

:global([h="48"]) {
  height: 48; }

:global([h="48!"]) {
  height: 48 !important; }

:global([w="50"]) {
  width: 50; }

:global([w="50!"]) {
  width: 50 !important; }

:global([h="50"]) {
  height: 50; }

:global([h="50!"]) {
  height: 50 !important; }

:global([w="60"]) {
  width: 60; }

:global([w="60!"]) {
  width: 60 !important; }

:global([h="60"]) {
  height: 60; }

:global([h="60!"]) {
  height: 60 !important; }

:global([w="64"]) {
  width: 64; }

:global([w="64!"]) {
  width: 64 !important; }

:global([h="64"]) {
  height: 64; }

:global([h="64!"]) {
  height: 64 !important; }

:global([w="72"]) {
  width: 72; }

:global([w="72!"]) {
  width: 72 !important; }

:global([h="72"]) {
  height: 72; }

:global([h="72!"]) {
  height: 72 !important; }

:global([w="80"]) {
  width: 80; }

:global([w="80!"]) {
  width: 80 !important; }

:global([h="80"]) {
  height: 80; }

:global([h="80!"]) {
  height: 80 !important; }

:global([w="96"]) {
  width: 96; }

:global([w="96!"]) {
  width: 96 !important; }

:global([h="96"]) {
  height: 96; }

:global([h="96!"]) {
  height: 96 !important; }

:global([w="100"]) {
  width: 100; }

:global([w="100!"]) {
  width: 100 !important; }

:global([h="100"]) {
  height: 100; }

:global([h="100!"]) {
  height: 100 !important; }

:global([w="120"]) {
  width: 120; }

:global([w="120!"]) {
  width: 120 !important; }

:global([h="120"]) {
  height: 120; }

:global([h="120!"]) {
  height: 120 !important; }

:global([w="128"]) {
  width: 128; }

:global([w="128!"]) {
  width: 128 !important; }

:global([h="128"]) {
  height: 128; }

:global([h="128!"]) {
  height: 128 !important; }

:global([w="140"]) {
  width: 140; }

:global([w="140!"]) {
  width: 140 !important; }

:global([h="140"]) {
  height: 140; }

:global([h="140!"]) {
  height: 140 !important; }

:global([w="150"]) {
  width: 150; }

:global([w="150!"]) {
  width: 150 !important; }

:global([h="150"]) {
  height: 150; }

:global([h="150!"]) {
  height: 150 !important; }

:global([w="200"]) {
  width: 200; }

:global([w="200!"]) {
  width: 200 !important; }

:global([h="200"]) {
  height: 200; }

:global([h="200!"]) {
  height: 200 !important; }

:global([w="240"]) {
  width: 240; }

:global([w="240!"]) {
  width: 240 !important; }

:global([h="240"]) {
  height: 240; }

:global([h="240!"]) {
  height: 240 !important; }

:global([w="300"]) {
  width: 300; }

:global([w="300!"]) {
  width: 300 !important; }

:global([h="300"]) {
  height: 300; }

:global([h="300!"]) {
  height: 300 !important; }

:global([w="10%%"]) {
  width: 10%; }

:global([w="10%%!"]) {
  width: 10% !important; }

:global([h="10%%"]) {
  height: 10%; }

:global([h="10%%!"]) {
  height: 10% !important; }

:global([w="11.1%%"]) {
  width: 11.1%; }

:global([w="11.1%%!"]) {
  width: 11.1% !important; }

:global([h="11.1%%"]) {
  height: 11.1%; }

:global([h="11.1%%!"]) {
  height: 11.1% !important; }

:global([w="12.5%%"]) {
  width: 12.5%; }

:global([w="12.5%%!"]) {
  width: 12.5% !important; }

:global([h="12.5%%"]) {
  height: 12.5%; }

:global([h="12.5%%!"]) {
  height: 12.5% !important; }

:global([w="14.3%%"]) {
  width: 14.3%; }

:global([w="14.3%%!"]) {
  width: 14.3% !important; }

:global([h="14.3%%"]) {
  height: 14.3%; }

:global([h="14.3%%!"]) {
  height: 14.3% !important; }

:global([w="16.7%%"]) {
  width: 16.7%; }

:global([w="16.7%%!"]) {
  width: 16.7% !important; }

:global([h="16.7%%"]) {
  height: 16.7%; }

:global([h="16.7%%!"]) {
  height: 16.7% !important; }

:global([w="20%%"]) {
  width: 20%; }

:global([w="20%%!"]) {
  width: 20% !important; }

:global([h="20%%"]) {
  height: 20%; }

:global([h="20%%!"]) {
  height: 20% !important; }

:global([w="25%%"]) {
  width: 25%; }

:global([w="25%%!"]) {
  width: 25% !important; }

:global([h="25%%"]) {
  height: 25%; }

:global([h="25%%!"]) {
  height: 25% !important; }

:global([w="33.3%%"]) {
  width: 33.3%; }

:global([w="33.3%%!"]) {
  width: 33.3% !important; }

:global([h="33.3%%"]) {
  height: 33.3%; }

:global([h="33.3%%!"]) {
  height: 33.3% !important; }

:global([w="50%%"]) {
  width: 50%; }

:global([w="50%%!"]) {
  width: 50% !important; }

:global([h="50%%"]) {
  height: 50%; }

:global([h="50%%!"]) {
  height: 50% !important; }

:global([w="100%%"]) {
  width: 100%; }

:global([w="100%%!"]) {
  width: 100% !important; }

:global([h="100%%"]) {
  height: 100%; }

:global([h="100%%!"]) {
  height: 100% !important; }

:global([w="tenth"]) {
  width: "10%"; }

:global([w="ninth"]) {
  width: "11.1%"; }

:global([w="eighth"]) {
  width: "12.5%"; }

:global([w="seventh"]) {
  width: "14.3%"; }

:global([w="sixth"]) {
  width: "16.7%"; }

:global([w="fifth"]) {
  width: "20%"; }

:global([w="fourth"]), :global([w="quarter"]) {
  width: "25%"; }

:global([w="third"]) {
  width: "33.3%"; }

:global([w="half"]) {
  width: "50%"; }

:global([w="whole"]), :global([w="full"]) {
  width: "100%"; }

:global([w="tenth!"]) {
  width: "10%" !important; }

:global([w="ninth!"]) {
  width: "11.1%" !important; }

:global([w="eighth!"]) {
  width: "12.5%" !important; }

:global([w="seventh!"]) {
  width: "14.3%" !important; }

:global([w="sixth!"]) {
  width: "16.7%" !important; }

:global([w="fifth!"]) {
  width: "20%" !important; }

:global([w="fourth!"]), :global([w="quarter!"]) {
  width: "25%" !important; }

:global([w="third!"]) {
  width: "33.3%" !important; }

:global([w="half!"]) {
  width: "50%" !important; }

:global([w="whole!"]), :global([w="full!"]) {
  width: "100%" !important; }

:global([h="tenth"]) {
  height: "10%"; }

:global([h="ninth"]) {
  height: "11.1%"; }

:global([h="eighth"]) {
  height: "12.5%"; }

:global([h="seventh"]) {
  height: "14.3%"; }

:global([h="sixth"]) {
  height: "16.7%"; }

:global([h="fifth"]) {
  height: "20%"; }

:global([h="fourth"]), :global([h="quarter"]) {
  height: "25%"; }

:global([h="third"]) {
  height: "33.3%"; }

:global([h="half"]) {
  height: "50%"; }

:global([h="whole"]), :global([h="full"]) {
  height: "100%"; }

:global([h="tenth!"]) {
  height: "10%" !important; }

:global([h="ninth!"]) {
  height: "11.1%" !important; }

:global([h="eighth!"]) {
  height: "12.5%" !important; }

:global([h="seventh!"]) {
  height: "14.3%" !important; }

:global([h="sixth!"]) {
  height: "16.7%" !important; }

:global([h="fifth!"]) {
  height: "20%" !important; }

:global([h="fourth!"]), :global([h="quarter!"]) {
  height: "25%" !important; }

:global([h="third!"]) {
  height: "33.3%" !important; }

:global([h="half!"]) {
  height: "50%" !important; }

:global([h="whole!"]), :global([h="full!"]) {
  height: "100%" !important; }

:global([padding-below-0]) {
  padding-bottom: var(--fine-spacing-0); }

:global([padding-below-xxs]) {
  padding-bottom: var(--fine-spacing-xxs); }

:global([padding-below-xs]) {
  padding-bottom: var(--fine-spacing-xs); }

:global([padding-below-s]) {
  padding-bottom: var(--fine-spacing-s); }

:global([padding-below-m]) {
  padding-bottom: var(--fine-spacing-m); }

:global([padding-below-l]) {
  padding-bottom: var(--fine-spacing-l); }

:global([padding-below-xl]) {
  padding-bottom: var(--fine-spacing-xl); }

:global([padding-below-xxl]) {
  padding-bottom: var(--fine-spacing-xxl); }

:global([padding-left-0]) {
  padding-left: var(--fine-spacing-0); }

:global([padding-left-xxs]) {
  padding-left: var(--fine-spacing-xxs); }

:global([padding-left-xs]) {
  padding-left: var(--fine-spacing-xs); }

:global([padding-left-s]) {
  padding-left: var(--fine-spacing-s); }

:global([padding-left-m]) {
  padding-left: var(--fine-spacing-m); }

:global([padding-left-l]) {
  padding-left: var(--fine-spacing-l); }

:global([padding-left-xl]) {
  padding-left: var(--fine-spacing-xl); }

:global([padding-left-xxl]) {
  padding-left: var(--fine-spacing-xxl); }

:global([margin-below-0]) {
  margin-bottom: var(--fine-spacing-0); }

:global([margin-below-xxs]) {
  margin-bottom: var(--fine-spacing-xxs); }

:global([margin-below-xs]) {
  margin-bottom: var(--fine-spacing-xs); }

:global([margin-below-s]) {
  margin-bottom: var(--fine-spacing-s); }

:global([margin-below-m]) {
  margin-bottom: var(--fine-spacing-m); }

:global([margin-below-l]) {
  margin-bottom: var(--fine-spacing-l); }

:global([margin-below-xl]) {
  margin-bottom: var(--fine-spacing-xl); }

:global([margin-below-xxl]) {
  margin-bottom: var(--fine-spacing-xxl); }

:global([margin-left-0]) {
  margin-left: var(--fine-spacing-0); }

:global([margin-left-xxs]) {
  margin-left: var(--fine-spacing-xxs); }

:global([margin-left-xs]) {
  margin-left: var(--fine-spacing-xs); }

:global([margin-left-s]) {
  margin-left: var(--fine-spacing-s); }

:global([margin-left-m]) {
  margin-left: var(--fine-spacing-m); }

:global([margin-left-l]) {
  margin-left: var(--fine-spacing-l); }

:global([margin-left-xl]) {
  margin-left: var(--fine-spacing-xl); }

:global([margin-left-xxl]) {
  margin-left: var(--fine-spacing-xxl); }

:global(span[spacer]) {
  padding: 0px 4px; }

</style>