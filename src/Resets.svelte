<style>
:global(*) {
  box-sizing: border-box;
  margin: 0px;
  padding: 0px;
  text-align: left;
  font-weight: inherit;
  border-radius: 0px; }

:global(*:focus) {
  outline: none;
  box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px 0px inset; }

:global(div) {
  position: relative; }

:global(button), :global(input[type="button"]), :global(input) {
  border: none;
  background: transparent;
  font-family: var(--font-family-primary); }

  :global(button:focus), :global(input[type="button"]:focus), :global(input:focus) {
    outline: none; }

:global(a), :global(a > em) {
  text-decoration: none; }

:global(a > em) {
  font-style: normal; }

:global(a:hover > em) {
  text-decoration: underline; }

:global(a), :global(a:hover), :global(a:visited), :global(a:active) {
  color: var(--black); }

:global(html), :global(body) {
  min-width: var(--breakpoint-min);
  width: 100%;
  height: 100%; }

:global(ul), :global(ol) {
  list-style-type: none; }

:global(ul[unstyled]), :global(ol[unstyled]) {
  list-style-type: none !important; }

  :global(ul[unstyled] li), :global(ol[unstyled] li) {
    margin-left: 0px !important; }

:global(table) {
  border-spacing: 0;
  border-collapse: collapse; }

  :global(table td), :global(table th) {
    vertical-align: top; }

:global(details summary::-webkit-details-marker) {
  display: none;
  font-size: 0px; }

:global(a), :global(b), :global(i), :global(strong), :global(em) {
  font-weight: inherit;
  text-decoration: inherit; }

:global(hr) {
  border-top: 1px solid var(--lightest-gray); }


</style>