# Crystal Kizor — Stage 1 Assessment

A mobile-first, single-page personal-brand landing page built with semantic HTML, CSS and vanilla JavaScript. It intentionally uses no build step, package manager or framework so it can be edited and deployed from a phone.

## Features
- Responsive editorial design and mobile navigation
- Clear hierarchy across all seven initiatives in the assessment brief
- Audience pathways to help visitors find a relevant next step
- Interactive initiative filters
- Contact links that prefill an enquiry subject
- Semantic landmarks, keyboard focus styles, alt text and reduced-motion support
- Lazy loading for secondary imagery

## Run and deploy from a phone
1. Download and unzip this project.
2. Open GitHub in your phone browser and create a **public** repository named `crystal-kizor-assessment`.
3. Choose **Add file → Upload files** and upload `index.html`, `README.md`, and the `submission` folder. (If your phone's file picker cannot upload a folder, upload the documents inside it individually.)
4. Commit the upload.
5. For a live link using GitHub Pages: open repository **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save. Wait for the published URL.
6. Alternatively, sign in to Vercel, choose **Add New → Project**, import the GitHub repository, keep the framework preset as **Other**, set build command and output directory to blank/default, then deploy. Since `index.html` is at the root, no build is required.

## Important before submission
- This is a concept implementation based on the assessment brief. Replace the generic image choices with the supplied professional photos/logos if available.
- Confirm the correct official contact email and official social/brand URLs before publishing. The `hello@crystalkizor.com` address is a placeholder, not a verified contact.
- Add verified project links where available. Do not present invented projects, testimonials, metrics or credentials as facts.
- The supplied reference website is inspiration only; this implementation uses its own layout and copy.
- Test the deployed link on your phone, including menu, filters, links and image loading.

## Technology choice
A single static HTML page with custom CSS and vanilla JavaScript avoids mobile build friction and reduces deployment risk. For this assessment, fast loading, responsive design, clear content hierarchy and understandable source code matter more than using a framework solely for its name.
