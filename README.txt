SAI VENKAT & SATHVIKA — WEDDING WEBSITE VERSION 2 (MUHURTHAM ONLY)
=================================================================
Based on Final Version 1. Version 1 is not modified.

This release repairs the link-preview metadata for the ACTUAL published Wasmer website:
  https://staticfile-ss-mdu.wasmer.app/

Preview image: assets/wedding-v1-original-social-preview-2026.jpg
This is a byte-for-byte copy of Version 1's approved og-preview.jpg (1200 x 630).
The title remains Sai Venkat & Sathvika | Kalyana Vaibhogam.
The social preview description is:
  With love and joy, we invite you to celebrate this special occasion with us.

This also retains the previously corrected Version 2 RSVP screens and code:
Yes: Name required, Phone and Message optional.
No: Name and Phone required, Message optional, with WhatsApp livestream promise.
The No thank-you screen displays the original livestream illustration.
RSVP requests use the NEW independent Version 2 Google Apps Script endpoint.

DEPLOYMENT
Publish the CONTENTS of this directory to the root of the Wasmer website.
The expected deployed paths must work:
  https://staticfile-ss-mdu.wasmer.app/
  https://staticfile-ss-mdu.wasmer.app/assets/wedding-v1-original-social-preview-2026.jpg
Deploying this ZIP alone cannot override a social app's existing cached preview.
Try a freshly query-suffixed SHARE URL after deployment to cause a new link crawl:
  https://staticfile-ss-mdu.wasmer.app/?v=preview2
(The question mark suffix should not change which page the guest sees.)

IMPORTANT
The live Wasmer origin could not be accessed from the build environment, so
we verified local HTML/assets and cannot guarantee live crawler access.
Verify that the preview image URL opens without login, then share the site.
Version 1 project/code and backend are not changed by this ZIP.
