# Verifiable Agent Safety workshop website

Website for the proposed ICLR 2027 workshop, adapted from the original workshop template using `../proposal/main.tex`.

The original Bootstrap layout, stylesheet, shared header/navigation/footer, circular organizer photos, and scroll-to-top behavior are retained. Workshop-specific text, dates, links, and organizer entries are updated. Bo Li and Alina Oprea are listed as confirmed speakers.

Run `python3 -m http.server 8767 --bind 127.0.0.1` in this directory and open http://127.0.0.1:8767. Use an HTTP server so `load-templates.js` can load the shared HTML fragments. Bootstrap and its JavaScript dependencies load from the template's original CDNs.

Edit `index.html` and `cfp.html` for workshop content, `header.html` for the title/date, `navbar.html` for navigation, and `footer.html` for contact information. Confirm the tentative dates, venue, submission portal, and formatting template before launch. The inherited sponsorship PDF and unused photos are not linked.
