<style global>

[shadow="vertical"], [shadow="top"] {
  box-shadow: 0px 2px 5px 0px var(--box-shadow); }

[shadow="bottom"] {
  box-shadow: 0px 0px 2px 5px var(--box-shadow); }

[shadow="right"], [shadow="horizontal"] {
  box-shadow: 2px 0px 5px 0px var(--box-shadow); }

[shadow="left"] {
  box-shadow: -2px 0px 5px 0px var(--box-shadow); }

[type="overlay"] {
  display: none;
  height: 100%;
  width: 100%;
  position: fixed;
  z-index: var(--z-index-overlay);
  top: 0;
  left: 0;
  background-color: var(--overlay);
  opacity: var(--overlay-opacity); }
  [type="overlay"][clear] {
    background-color: transparent; }
  [type="overlay"][open="true"] {
    display: block; }

[show] {
  display: block; }

[show="false"], [hide="true"], .hidden {
  display: none; }

[show="false!"], [hide="true!"] {
  display: none !important; }

[show="true!"] {
  display: block !important; }

[c*="v"] {
  position: relative;
  top: 50%;
  transform: translateY(-50%);
  /* prefixes needed for cross-browser support */
  -ms-transform: translateY(-50%);
  -webkit-transform: translateY(-50%); }

[c*="h"] {
  margin: 0 auto;
  /* prefixes needed for cross-browser support */ }

[scroll] {
  overflow: auto; }

[scroll-x] {
  overflow-x: scroll; }

[scroll-y] {
  overflow: scroll; }

[noscroll] {
  overflow: hidden; }

[w="8"] {
  width: 8; }

[w="8!"] {
  width: 8 !important; }

[h="8"] {
  height: 8; }

[h="8!"] {
  height: 8 !important; }

[w="10"] {
  width: 10; }

[w="10!"] {
  width: 10 !important; }

[h="10"] {
  height: 10; }

[h="10!"] {
  height: 10 !important; }

[w="12"] {
  width: 12; }

[w="12!"] {
  width: 12 !important; }

[h="12"] {
  height: 12; }

[h="12!"] {
  height: 12 !important; }

[w="24"] {
  width: 24; }

[w="24!"] {
  width: 24 !important; }

[h="24"] {
  height: 24; }

[h="24!"] {
  height: 24 !important; }

[w="36"] {
  width: 36; }

[w="36!"] {
  width: 36 !important; }

[h="36"] {
  height: 36; }

[h="36!"] {
  height: 36 !important; }

[w="40"] {
  width: 40; }

[w="40!"] {
  width: 40 !important; }

[h="40"] {
  height: 40; }

[h="40!"] {
  height: 40 !important; }

[w="48"] {
  width: 48; }

[w="48!"] {
  width: 48 !important; }

[h="48"] {
  height: 48; }

[h="48!"] {
  height: 48 !important; }

[w="50"] {
  width: 50; }

[w="50!"] {
  width: 50 !important; }

[h="50"] {
  height: 50; }

[h="50!"] {
  height: 50 !important; }

[w="60"] {
  width: 60; }

[w="60!"] {
  width: 60 !important; }

[h="60"] {
  height: 60; }

[h="60!"] {
  height: 60 !important; }

[w="64"] {
  width: 64; }

[w="64!"] {
  width: 64 !important; }

[h="64"] {
  height: 64; }

[h="64!"] {
  height: 64 !important; }

[w="72"] {
  width: 72; }

[w="72!"] {
  width: 72 !important; }

[h="72"] {
  height: 72; }

[h="72!"] {
  height: 72 !important; }

[w="80"] {
  width: 80; }

[w="80!"] {
  width: 80 !important; }

[h="80"] {
  height: 80; }

[h="80!"] {
  height: 80 !important; }

[w="96"] {
  width: 96; }

[w="96!"] {
  width: 96 !important; }

[h="96"] {
  height: 96; }

[h="96!"] {
  height: 96 !important; }

[w="100"] {
  width: 100; }

[w="100!"] {
  width: 100 !important; }

[h="100"] {
  height: 100; }

[h="100!"] {
  height: 100 !important; }

[w="120"] {
  width: 120; }

[w="120!"] {
  width: 120 !important; }

[h="120"] {
  height: 120; }

[h="120!"] {
  height: 120 !important; }

[w="128"] {
  width: 128; }

[w="128!"] {
  width: 128 !important; }

[h="128"] {
  height: 128; }

[h="128!"] {
  height: 128 !important; }

[w="140"] {
  width: 140; }

[w="140!"] {
  width: 140 !important; }

[h="140"] {
  height: 140; }

[h="140!"] {
  height: 140 !important; }

[w="150"] {
  width: 150; }

[w="150!"] {
  width: 150 !important; }

[h="150"] {
  height: 150; }

[h="150!"] {
  height: 150 !important; }

[w="200"] {
  width: 200; }

[w="200!"] {
  width: 200 !important; }

[h="200"] {
  height: 200; }

[h="200!"] {
  height: 200 !important; }

[w="240"] {
  width: 240; }

[w="240!"] {
  width: 240 !important; }

[h="240"] {
  height: 240; }

[h="240!"] {
  height: 240 !important; }

[w="300"] {
  width: 300; }

[w="300!"] {
  width: 300 !important; }

[h="300"] {
  height: 300; }

[h="300!"] {
  height: 300 !important; }

[w="10%%"] {
  width: 10%; }

[w="10%%!"] {
  width: 10% !important; }

[h="10%%"] {
  height: 10%; }

[h="10%%!"] {
  height: 10% !important; }

[w="11.1%%"] {
  width: 11.1%; }

[w="11.1%%!"] {
  width: 11.1% !important; }

[h="11.1%%"] {
  height: 11.1%; }

[h="11.1%%!"] {
  height: 11.1% !important; }

[w="12.5%%"] {
  width: 12.5%; }

[w="12.5%%!"] {
  width: 12.5% !important; }

[h="12.5%%"] {
  height: 12.5%; }

[h="12.5%%!"] {
  height: 12.5% !important; }

[w="14.3%%"] {
  width: 14.3%; }

[w="14.3%%!"] {
  width: 14.3% !important; }

[h="14.3%%"] {
  height: 14.3%; }

[h="14.3%%!"] {
  height: 14.3% !important; }

[w="16.7%%"] {
  width: 16.7%; }

[w="16.7%%!"] {
  width: 16.7% !important; }

[h="16.7%%"] {
  height: 16.7%; }

[h="16.7%%!"] {
  height: 16.7% !important; }

[w="20%%"] {
  width: 20%; }

[w="20%%!"] {
  width: 20% !important; }

[h="20%%"] {
  height: 20%; }

[h="20%%!"] {
  height: 20% !important; }

[w="25%%"] {
  width: 25%; }

[w="25%%!"] {
  width: 25% !important; }

[h="25%%"] {
  height: 25%; }

[h="25%%!"] {
  height: 25% !important; }

[w="33.3%%"] {
  width: 33.3%; }

[w="33.3%%!"] {
  width: 33.3% !important; }

[h="33.3%%"] {
  height: 33.3%; }

[h="33.3%%!"] {
  height: 33.3% !important; }

[w="50%%"] {
  width: 50%; }

[w="50%%!"] {
  width: 50% !important; }

[h="50%%"] {
  height: 50%; }

[h="50%%!"] {
  height: 50% !important; }

[w="100%%"] {
  width: 100%; }

[w="100%%!"] {
  width: 100% !important; }

[h="100%%"] {
  height: 100%; }

[h="100%%!"] {
  height: 100% !important; }

[w="tenth"] {
  width: "10%"; }

[w="ninth"] {
  width: "11.1%"; }

[w="eighth"] {
  width: "12.5%"; }

[w="seventh"] {
  width: "14.3%"; }

[w="sixth"] {
  width: "16.7%"; }

[w="fifth"] {
  width: "20%"; }

[w="fourth"], [w="quarter"] {
  width: "25%"; }

[w="third"] {
  width: "33.3%"; }

[w="half"] {
  width: "50%"; }

[w="whole"], [w="full"] {
  width: "100%"; }

[w="tenth!"] {
  width: "10%" !important; }

[w="ninth!"] {
  width: "11.1%" !important; }

[w="eighth!"] {
  width: "12.5%" !important; }

[w="seventh!"] {
  width: "14.3%" !important; }

[w="sixth!"] {
  width: "16.7%" !important; }

[w="fifth!"] {
  width: "20%" !important; }

[w="fourth!"], [w="quarter!"] {
  width: "25%" !important; }

[w="third!"] {
  width: "33.3%" !important; }

[w="half!"] {
  width: "50%" !important; }

[w="whole!"], [w="full!"] {
  width: "100%" !important; }

[h="tenth"] {
  height: "10%"; }

[h="ninth"] {
  height: "11.1%"; }

[h="eighth"] {
  height: "12.5%"; }

[h="seventh"] {
  height: "14.3%"; }

[h="sixth"] {
  height: "16.7%"; }

[h="fifth"] {
  height: "20%"; }

[h="fourth"], [h="quarter"] {
  height: "25%"; }

[h="third"] {
  height: "33.3%"; }

[h="half"] {
  height: "50%"; }

[h="whole"], [h="full"] {
  height: "100%"; }

[h="tenth!"] {
  height: "10%" !important; }

[h="ninth!"] {
  height: "11.1%" !important; }

[h="eighth!"] {
  height: "12.5%" !important; }

[h="seventh!"] {
  height: "14.3%" !important; }

[h="sixth!"] {
  height: "16.7%" !important; }

[h="fifth!"] {
  height: "20%" !important; }

[h="fourth!"], [h="quarter!"] {
  height: "25%" !important; }

[h="third!"] {
  height: "33.3%" !important; }

[h="half!"] {
  height: "50%" !important; }

[h="whole!"], [h="full!"] {
  height: "100%" !important; }

[padding-below-0] {
  padding-bottom: var(--fine-spacing-0); }

[padding-below-xxs] {
  padding-bottom: var(--fine-spacing-xxs); }

[padding-below-xs] {
  padding-bottom: var(--fine-spacing-xs); }

[padding-below-s] {
  padding-bottom: var(--fine-spacing-s); }

[padding-below-m] {
  padding-bottom: var(--fine-spacing-m); }

[padding-below-l] {
  padding-bottom: var(--fine-spacing-l); }

[padding-below-xl] {
  padding-bottom: var(--fine-spacing-xl); }

[padding-below-xxl] {
  padding-bottom: var(--fine-spacing-xxl); }

[padding-left-0] {
  padding-left: var(--fine-spacing-0); }

[padding-left-xxs] {
  padding-left: var(--fine-spacing-xxs); }

[padding-left-xs] {
  padding-left: var(--fine-spacing-xs); }

[padding-left-s] {
  padding-left: var(--fine-spacing-s); }

[padding-left-m] {
  padding-left: var(--fine-spacing-m); }

[padding-left-l] {
  padding-left: var(--fine-spacing-l); }

[padding-left-xl] {
  padding-left: var(--fine-spacing-xl); }

[padding-left-xxl] {
  padding-left: var(--fine-spacing-xxl); }

[margin-below-0] {
  margin-bottom: var(--fine-spacing-0); }

[margin-below-xxs] {
  margin-bottom: var(--fine-spacing-xxs); }

[margin-below-xs] {
  margin-bottom: var(--fine-spacing-xs); }

[margin-below-s] {
  margin-bottom: var(--fine-spacing-s); }

[margin-below-m] {
  margin-bottom: var(--fine-spacing-m); }

[margin-below-l] {
  margin-bottom: var(--fine-spacing-l); }

[margin-below-xl] {
  margin-bottom: var(--fine-spacing-xl); }

[margin-below-xxl] {
  margin-bottom: var(--fine-spacing-xxl); }

[margin-left-0] {
  margin-left: var(--fine-spacing-0); }

[margin-left-xxs] {
  margin-left: var(--fine-spacing-xxs); }

[margin-left-xs] {
  margin-left: var(--fine-spacing-xs); }

[margin-left-s] {
  margin-left: var(--fine-spacing-s); }

[margin-left-m] {
  margin-left: var(--fine-spacing-m); }

[margin-left-l] {
  margin-left: var(--fine-spacing-l); }

[margin-left-xl] {
  margin-left: var(--fine-spacing-xl); }

[margin-left-xxl] {
  margin-left: var(--fine-spacing-xxl); }

span[spacer] {
  padding: 0px 4px; }

</style>