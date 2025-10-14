HOW TO ADD YOUR WORK (no coding required)

1) VIDEOS (easiest = YouTube/Vimeo)
   - Upload your video to YouTube or Vimeo.
   - Copy the "Share" embed link.
   - Open videos.html, find an <iframe ...> and replace the src with your link.
   - Or duplicate an <article> block to add more videos.

   Hosting MP4s directly on GitHub Pages is possible for small files, but for anything large, use YouTube/Vimeo. GitHub has a size limit (~100 MB per file on push) and no streaming optimizations.

2) PHOTOS
   - Put your JPG/PNG files into assets/photos/.
   - Open photos.html and duplicate one of the <a><img></a> items with your filenames.

3) GRAPHIC DESIGN
   - Put PNG/JPG files into assets/design/.
   - Open design.html and duplicate an item pointing at your new files.

4) TEXT EDITS
   - Edit any page directly on GitHub: open file → pencil icon (edit) → make change → Commit changes.

5) PUBLISHING CHANGES
   - GitHub Pages auto-redeploys when you commit. Refresh your live site link after a minute.

FOLDER LAYOUT:
index.html
videos.html
photos.html
design.html
contact.html
/assets
  style.css
  /photos (your images)
  /design (your images)
  /videos (optional; small mp4s only)
