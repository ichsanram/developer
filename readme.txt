1. DOCTYPEs are required for legacy reasons. When omitted, browsers tend to use a different rendering mode that is incompatible with some specifications. Including the DOCTYPE in a document ensures that the browser makes a best-effort attempt at following the relevant specifications.

2. The data-attributes is used to store custom data private to the page or application, The data-attributes gives us the ability to embed custom data attributes on all HTML elements

   yang disimpan dalam atribut data kepada pengguna dengan bantuan fungsu atribut.
3. - A cookie is a small file that the server embeds on the user's computer. Each time the same computer requests a page with a browser.
   - The sessionStorage property allows you to access a session Storage object for the current origin, sessionStorage will clear automatically once page session will expire.
   - The localStorage object stores data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.

4. - resetting CSS aim to remove all built-in browser styling. Standard elements like H1-6, p, strong, em, et cetera end up looking exactly alike, having no decoration at all.
   - Normalize CSS aims to make built-in browser styling consistent across browsers. Elements like H1-6 will appear bold, larger et cetera in a consistent way across browsers.

   I choose Normalize CSS.
   - Normalize css preserves useful defaults rather than "unstyling" everything.
   - Normalize css corrects some common bugs that are out of scope for reset.css.
   - Normalize css doesn't clutter your dev tools.
   - Normalize css is more modular.
   - Normalize css has better documentation.

5. When document.write() is executed after page load, it replaces the entire header and body tag with the given parameter value in string.