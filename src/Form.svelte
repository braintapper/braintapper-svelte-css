<style>

:global(textarea), 
:global(input), 
:global(select), 
:global(button[type="select"]) {
  border-radius: var(--corner-s);
  padding: var(--fine-spacing-s) var(--fine-spacing-m);
  border: 1px solid var(--input-border);
  font-family: var(--font-family-primary), -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-size: var(--font-s);
  width: 100%; }

  :global(textarea[required]),
  :global(textarea[invalid="true"]),
  :global(input[required]),
  :global(input[invalid="true"]),
  :global(select[required]), 
  :global(select[invalid="true"]), 
  :global(button[type="select"][required]), 
  :global(button[type="select"][invalid="true"]) {
    border-color: var(--critical); }

  :global(textarea[disabled]), 
  :global(input[disabled]), 
  :global(select[disabled]), 
  :global(button[type="select"][disabled]) {
    color: var(--dark-gray); }

  :global(textarea option), 
  :global(input option), 
  :global(select option), 
  :global(button[type="select"] option) {
    padding: var(--fine-spacing-s) var(--fine-spacing-m);
    font-size: var(--font-s); }

:global(field) {
  display: block;
  margin: var(--fine-spacing-l) 0px; }

:global(aside[type="field"]), 
:global(field aside) {
  display: inline-block;
  font-size: var(--font-xs);
  margin: var(--fine-spacing-xs) var(--fine-spacing-0);
  color: var(--neutral); }

  :global(aside[type="field"][required]), 
  :global(aside[type="field"][invalid="true"]), 
  :global(aside[type="field"][critical]), 
  :global(field aside[required]), 
  :global(field aside[invalid="true"]), 
  :global(field aside[critical]) {
    color: var(--critical); }

:global([type="form"]) {
  padding: var(--spacing-s); }


</style>