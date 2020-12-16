<style global>

textarea, input, select, button[type="select"] {
  border-radius: var(--corner-s);
  padding: var(--fine-spacing-s) var(--fine-spacing-m);
  border: 1px solid var(--input-border);
  font-family: var(--font-family-primary), -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-size: var(--font-s);
  width: 100%; }
  textarea[required], textarea[invalid="true"], input[required], input[invalid="true"], select[required], select[invalid="true"], button[type="select"][required], button[type="select"][invalid="true"] {
    border-color: var(--critical); }
  textarea[disabled], input[disabled], select[disabled], button[type="select"][disabled] {
    color: var(--dark-gray); }
  textarea option, input option, select option, button[type="select"] option {
    padding: var(--fine-spacing-s) var(--fine-spacing-m);
    font-size: var(--font-s); }

field {
  display: block;
  margin: var(--fine-spacing-l) 0px; }

aside[type="field"], field aside {
  display: inline-block;
  font-size: var(--font-xs);
  margin: var(--fine-spacing-xs) var(--fine-spacing-0);
  color: var(--neutral); }
  aside[type="field"][required], aside[type="field"][invalid="true"], aside[type="field"][critical], field aside[required], field aside[invalid="true"], field aside[critical] {
    color: var(--critical); }

[type="form"] {
  padding: var(--spacing-s); }


</style>