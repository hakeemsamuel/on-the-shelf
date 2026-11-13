# On the Shelf · deploy folder

`index.html` is a copy of `../On-the-Shelf.html`. Copy it again after edits, then redeploy.

    cp ../On-the-Shelf.html index.html
    npx vercel --prod

The first run asks you to log in and name the project (e.g. `on-the-shelf`).
The production link stays the same on every redeploy, so a QR code made from it keeps working.
