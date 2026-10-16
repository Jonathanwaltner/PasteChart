# PasteChart

A free chart maker: paste or type data, pick a chart, download a PNG. Plain HTML, CSS and JavaScript, no build step.

## Files

- `index.html` is the whole tool. HTML at the top, then the script at the bottom. Comments mark each part.
- `privacy.html` is the privacy policy. Update the date and contact email if they change.
- `guides/` has three helpful articles. They bring in search traffic and give ad networks something to review.
- `assets/guides.css` styles the guide pages and the privacy page.

## Things you will edit

1. **Site name and Pro unlock:** the `CONFIG` block at the top of the script in `index.html`. Set `unlockCode` to your own secret. Paste your payment link into `payLink` to show the unlock box.
2. **Search Console:** paste the verification tag into the marked comment near the top of `index.html`.
3. **Ads:** paste ad code into the three marked ad slots (left rail, right rail, and the one under the tool) after an ad network approves you.
4. **Affiliate links:** the guides have marked spots. Only add products you have really used, and include the disclosure Amazon requires.

## Pro and the free plan

Free: bars, horizontal bars, lines and pie, with a small watermark. Pro: stacked bars, area, doughnut and scatter, no watermark. Pro is unlocked with one shared code, so it works on the honor system. Anyone who edits the page can bypass it.

## Updating the live site

Edit the files, then on GitHub use Add file, Upload files, drop in the changed files, and commit. The site refreshes in a minute or two.
