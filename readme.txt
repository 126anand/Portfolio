Anand Sharma — Portfolio Website
=================================

SETUP INSTRUCTIONS
------------------

1. CONTACT FORM (Formspree):
   - Sign up free at https://formspree.io
   - Create a new form and copy your Form ID (looks like: xabc1234)
   - Open index.html and find this line:
       action="https://formspree.io/f/YOUR_FORMSPREE_ID"
   - Replace YOUR_FORMSPREE_ID with your actual ID
   - Example: action="https://formspree.io/f/xabc1234"

2. SOCIAL LINKS:
   - Open index.html and scroll to the <footer> section
   - Update the GitHub, LinkedIn, Twitter, Facebook, Instagram links
     with your actual profile URLs

3. GITHUB PAGES DEPLOYMENT:
   - Push this folder to a GitHub repository
   - Go to Settings → Pages → Source: main branch / root
   - Your site will be live at https://yourusername.github.io/repo-name

BUGS FIXED IN THIS VERSION
---------------------------
 - PHP backend removed (not compatible with GitHub Pages)
 - Contact form now uses Formspree (static-hosting compatible)
 - SMTP password that was exposed in php/send-email.php is gone
 - Broken nav dropdown links removed (index-video.html etc. didn't exist)
 - Social links fixed (were pointing to login pages)
 - Duplicate "required" attributes removed from form fields
 - Duplicate class="" attribute fixed on hero h1/h2
 - "[Name]" placeholder removed from Ryan Mullins testimonial
 - Typos fixed: "reponsive", "abotic", "Organzing"
 - Trailing colons removed from blog post titles
 - body user-select:none removed (was blocking all text selection)
 - Favicon no longer depends on external domain
 - Email/phone contact links now use proper mailto: protocol
 - Dynamic copyright year (no more document.write)
 - All img alt attributes improved for accessibility
 - rel="noopener noreferrer" added to all external links
 - macOS .DS_Store files removed
 - PHP/composer/vendor files removed (not needed for static hosting)
