 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/ROADMAP.md b/ROADMAP.md
new file mode 100644
index 0000000000000000000000000000000000000000..08966e3fdbf571c3735b369f1aad620cc9f8a55c
--- /dev/null
+++ b/ROADMAP.md
@@ -0,0 +1,32 @@
+# Website and growth roadmap for Bhavani Electricals & Mitali Enterprises
+
+## 1. Build the website on GitHub Pages
+
+1. Create or open the GitHub repository named `bhavani-code.github.io`.
+2. Add the `index.html` and `styles.css` files from this project.
+3. Commit and push the files to the `main` branch.
+4. Open **Settings → Pages** in GitHub and choose the `main` branch as the source.
+5. Visit `https://bhavani-code.github.io` after GitHub finishes publishing.
+
+## 2. Improve the website content
+
+- Replace the CSS illustration with the real banner or original project photos.
+- Add a gallery of residential, commercial, and industrial installations.
+- Add customer reviews and Google review screenshots.
+- Add a frequently asked questions section covering pricing, maintenance, warranty, and subsidy guidance.
+- Add a WhatsApp button and a Google Form for free quote requests.
+
+## 3. Reach people and grow locally
+
+- Create a Google Business Profile for “Bhavani Electricals & Mitali Enterprises”.
+- Use keywords such as “solar installation in Nashik”, “rooftop solar Nashik”, and “commercial solar installer Nashik”.
+- Share the website link on WhatsApp, Instagram, Facebook, YouTube Shorts, and local business directories.
+- Ask every satisfied customer for a Google review and permission to post installation photos.
+- Partner with electricians, builders, housing societies, architects, and factory consultants for referrals.
+- Run a small monthly Google Ads or Meta Ads campaign targeting Nashik and nearby areas.
+
+## 4. Track enquiries
+
+- Add Google Analytics and Google Search Console.
+- Track calls, WhatsApp clicks, and form submissions.
+- Keep a spreadsheet or CRM with name, phone number, location, property type, system size, quote amount, and follow-up date.
 
EOF
)
