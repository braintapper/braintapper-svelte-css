<style>

:global(body) {
  font-family: var(--font-family-primary), -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-size: var(--font-s); }

:global(h1), :global(h2), :global(h3), :global(h4), :global(h5), :global(h6) {
  font-weight: var(--font-bold); }

:global(h1) {
  font-size: var(--font-xxl); }

:global(h2) {
  font-size: var(--font-xl); }

:global(h3) {
  font-size: var(--font-l); }

:global(h4) {
  font-size: var(--font-m); }

:global(h5) {
  font-size: var(--font-s); }

:global(h6) {
  font-size: var(--font-xs); }

:global(p) {
  font-size: var(--font-s); }

:global(small) {
  font-size: var(--font-xs); }

:global(pre), :global(code) {
  font-family: var(--font-family-monospace), "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace; }

:global(pre) {
  font-size: var(--font-s); }

:global(b) {
  font-weight: var(--font-bold); }

:global([type="content"] h1), :global(.content h1), :global([content] h1) {
  margin-top: var(--text-spacing-xxl);
  margin-bottom: var(--text-spacing-xxl); }

:global([type="content"] h2), :global(.content h2), :global([content] h2) {
  margin-top: var(--text-spacing-xxl);
  margin-bottom: var(--text-spacing-xl); }

:global([type="content"] h3),
   :global(.content h3),
   :global([content] h3) ){
  margin-top: var(--text-spacing-xxl);
  margin-bottom: var(--text-spacing-l); }

:global([type="content"] h4),
  :global( .content h4),
   :global([content] h4) {
  margin-top: var(--text-spacing-xxl);
  margin-bottom: var(--text-spacing-m); }

:global([type="content"] h5), :global(.content h5), :global([content] h5) {
  margin-top: var(--text-spacing-xxl);
  margin-bottom: var(--text-spacing-s); }

:global([type="content"] h6), :global(.content h6),:global( [content] h6) {
  margin-top: var(--text-spacing-xxl);
  margin-bottom: var(--text-spacing-xs);
  text-transform: uppercase; }

:global([type="content"] p), :global( [type="content"] ol), :global( [type="content"] ul), :global( [type="content"] table[type]), :global( [type="content"] pre), :global( [type="content"] blockquote), :global( .content p), :global( .content ol), :global( .content ul), :global( .content table[type]), :global( .content pre), :global( .content blockquote), :global( [content] p), :global( [content] ol), :global( [content] ul), :global( [content] table[type]), :global( [content] pre), :global( [content] blockquote) {
  margin-bottom: var(--text-spacing-s); }

:global([type="content"] blockquote), :global(.content blockquote), :global([content] blockquote) {
  margin-left: var(--spacing-l);
  margin-right: var(--spacing-l); }

:global([type="content"] pre), :global(.content pre), :global([content] pre) {
  background: var(--lightest-gray);
  padding: var(--text-spacing-s);
  border-radius: var(--corner-l); }

:global([type="content"] pre), :global([type="content"] code), :global(.content pre), :global(.content code), :global([content] pre), :global([content] code) {
  color: var(--code); }

:global([type="content"] ul), :global(.content ul), :global([content] ul) {
  list-style-type: disc; }
  :global([type="content"] ul ul), :global(.content ul ul), :global([content] ul ul) {
    list-style-type: circle; }
    :global([type="content"] ul ul ul), :global(.content ul ul ul), :global([content] ul ul ul) {
      list-style-type: disc; }
      :global([type="content"] ul ul ul ul), :global(.content ul ul ul ul), :global([content] ul ul ul ul) {
        list-style-type: circle; }
        :global([type="content"] ul ul ul ul ul), :global(.content ul ul ul ul ul), :global([content] ul ul ul ul ul) {
          list-style-type: disc; }
          :global([type="content"] ul ul ul ul ul ul), :global(.content ul ul ul ul ul ul), :global([content] ul ul ul ul ul ul) {
            list-style-type: circle; }
            :global([type="content"] ul ul ul ul ul ul ul), :global(.content ul ul ul ul ul ul ul), :global([content] ul ul ul ul ul ul ul) {
              list-style-type: disc; }
  :global([type="content"] ul li), :global(.content ul li), :global([content] ul li) {
    margin-left: var(--spacing-xs); }

:global([type="content"] ol), :global(.content ol), :global([content] ol) {
  list-style-type: decimal; }
  :global([type="content"] ol ol), :global(.content ol ol), :global([content] ol ol) {
    list-style-type: lower-alpha; }
    :global([type="content"] ol ol ol), :global(.content ol ol ol), :global([content] ol ol ol) {
      list-style-type: lower-roman; }
      :global([type="content"] ol ol ol ol), :global(.content ol ol ol ol), :global([content] ol ol ol ol) {
        list-style-type: decimal; }
        :global([type="content"] ol ol ol ol ol), :global(.content ol ol ol ol ol), :global([content] ol ol ol ol ol) {
          list-style-type: lower-alpha; }
          :global([type="content"] ol ol ol ol ol ol), :global(.content ol ol ol ol ol ol), :global([content] ol ol ol ol ol ol) {
            list-style-type: lower-roman; }
  :global([type="content"] ol li), :global(.content ol li), :global([content] ol li) {
    margin-left: var(--spacing-s); }

:global([type="content"] table[type] th), :global(.content table[type] th), :global([content] table[type] th) {
  font-weight: bold; }

:global([type="content"] table[type] td), :global([type="content"] table[type] th), :global(.content table[type] td), :global(.content table[type] th), :global([content] table[type] td), :global([content] table[type] th) {
  padding: var(--fine-spacing-xxs) var(--fine-spacing-s); }

:global([type="content"] table[type][type="standard"] tr), :global([type="content"] table[type][type="standard"] td), :global([type="content"] table[type][type="standard"] th), :global(.content table[type][type="standard"] tr), :global(.content table[type][type="standard"] td), :global(.content table[type][type="standard"] th), :global([content] table[type][type="standard"] tr), :global([content] table[type][type="standard"] td), :global([content] table[type][type="standard"] th) {
  border: 1px solid var(--black); }


</style>