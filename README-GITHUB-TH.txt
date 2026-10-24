MUDMEE MODERN — GitHub Pages upload guide

FILES
- index.html (main website file)
- images/ (product photos; keep this folder and filenames unchanged)

IMPORTANT: Do not upload the ZIP itself to GitHub Pages and expect it to run.

HOW TO PUBLISH USING THE GITHUB WEBSITE
1. Download and unzip this package on your phone/computer.
2. Open your GitHub repository.
3. Use Add file > Upload files. Upload index.html AND the images folder contents.
   The final repository layout should be:
     index.html
     images/everyday-jacket.jpg
     images/crafted-bag.jpg
     images/signature-scarf.jpg
   (The images must be in a folder named exactly `images`.)
4. Commit the changes to the `main` branch.
5. Open Settings > Pages. Under Build and deployment choose `Deploy from a branch`,
   branch `main`, folder `/(root)`, then Save.
6. Wait a few minutes and refresh the URL shown under Settings > Pages.

If you already enabled Pages and see 404, check that `index.html` is at the repository root,
not inside another folder, and that filename capitalization is exactly `index.html`.
