PARTNER & FUNDER LOGOS
======================

  eu-partners.jpg             The wide "Funded by the European Union" coalition
                              lockup. This one is FIXED above the scrolling row
                              (so it never scrolls off). Replace the file to update it.

  youth-empowerment-fund.jpg  }  These scroll in the moving strip.
  lupins-africa.jpg           }

TO CHANGE A LOGO
----------------
Drop in a new file with the same name. White or transparent background is best.

TO ADD A NEW PARTNER (2 steps)
------------------------------
1) Put the new logo in this folder, e.g.  my-partner.jpg

2) Open index.html, search for:  pm-track
   You'll see the scrolling list. Copy one line and point it at your file,
   placing it just before the line that says  <!-- ADD A PARTNER ... -->  :

     <div class="partner-tile"><img src="partners/my-partner.jpg" alt="My Partner"/></div>

   Save and refresh. It joins the scrolling strip automatically.

NOTES
-----
- Only edit the ONE list you see. The strip copies itself to loop smoothly -
  don't add your logo twice.
- New partners go in the scrolling strip, NOT in the fixed EU lockup above it.
- Not comfortable editing index.html? Send the logo + name and it can be added
  for you.
