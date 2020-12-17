<style global>

  :global(:root) {

    --font-family-primary: Hind;
    --font-family-primary-bold: Hind;

    --font-family-monospace: Cascadia;
    --font-family-monospace-bold: Cascadia;

    --font-normal: normal;
    --font-bold: bold;
    --font-xxl: 28px;
    --font-xl: 24px;
    --font-l: 20px;
    --font-m: 18px;
    --font-s: 14px;
    --font-xs: 11px;

}


:global(@font-face) {
  font-family: Hind;
  src: url("./fonts/Hind-Regular.ttf");
  font-weight: normal; }

:global(@font-face) {
  font-family: Hind;
  src: url("./fonts/Hind-SemiBold.ttf");
  font-weight: bold; }

:global(@font-face) {
  font-family: Cascadia;
  src: url("./fonts/Cascadia.ttf");
  font-weight: normal; }

:global(@font-face) {
  font-family: Cascadia;
  src: url("./fonts/Cascadia.ttf");
  font-weight: bold; }

</style>
