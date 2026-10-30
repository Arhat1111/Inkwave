INKWAVE delivery policy fix
Minimum merchandise order: INR 200.
INR 200-349.99: INR 69 shipping.
INR 350 or more: free shipping.

IMPORTANT: The uploaded ZIP does NOT include the Cloudflare Worker source code. The website requests authoritative totals from https://inkwaves-payments.arhatshah123.workers.dev and checks that the payment amount matches. You MUST update the Cloudflare Worker pricing logic to use merchandiseSubtotal >= 350 and redeploy it. Otherwise checkout may reject INR 350 orders due to a mismatch. Do not modify payment amounts only in browser code.

Upload all website files including js/ to your GitHub repository. Test INR 199, 200, 349, 350, and 351 with your Worker after deployment.
