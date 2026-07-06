V1 STATUS — updated
=====================================================
✅ Preview section removed completely (HTML, CSS, JS, and the
   lightbox all cleaned out — no dead code left behind).

✅ Real book covers in place:
   assets/covers/hero-book.webp, bonus-60.webp, animal-book.webp

✅ Payment badges now render — BUT READ THIS:
   assets/icons/applepay.svg, mada.svg, visa.svg, mastercard.svg
   are generic placeholder badges I drew myself (plain wordmarks/
   shapes in the site's own colors). They are NOT the official
   Apple Pay / mada / Visa / Mastercard logo files — I can't
   reproduce those trademarked marks without pulling the licensed
   assets from each provider's brand guidelines page.

   Before this goes live, replace these 4 files with the official
   SVGs (same filenames, same folder) so the payment row shows the
   real, recognizable marks customers expect to see at checkout.
   Shipping look-alike badges on a real payment page is a trust risk,
   not just a cosmetic one.

STILL OPEN
----------
- Paddle checkout: redirectToCheckout() in index.html is still a
  placeholder — search for "TODO(production)" to find where to drop
  in your real Paddle.Checkout.open() call once you have a price ID.

TESTIMONIALS
   Section remains removed until real, verifiable customer reviews exist.
