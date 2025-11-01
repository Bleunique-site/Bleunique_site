BLEUNIQUE: Navigating the Depths. Defining the Rarity.
This repository hosts the source code for the Bleunique integrated brand platform—a philosophical, creative, and commercial space built around the journey of spiritual awakening and the pursuit of uncompromised truth.
🌟 Mission & Philosophy
Bleunique is founded on a singular vision: to bring Clarity, Creativity, and Truth through deeply intentional work.
The core of the philosophy is expressed in two main pillars:
The Threshold (Grief, Awakening, & Transcendence)
This section is dedicated to the raw experience of loss and the profound spiritual awakening that follows. It serves as a space for shared vulnerability, inner work, and philosophical essays, anchored by the quote:
> "Loss broke illusions, my strength carried me through. Reality is not what we thought we knew."
> 
Cosmic Truths (Sovereignty & The 666 Awakening)
This content boldly reclaims the number 666, asserting it as the irrefutable signature of man based on the atomic structure of Carbon (6 Protons, 6 Neutrons, 6 Electrons). The message is one of self-sovereignty, unity, and confronting external fear to embrace the complete, divine self.
Site Features
The Bleunique platform integrates multiple functions into one responsive file:
 * The Studio: A service inquiry form for intentional design projects, built to capture client leads and store them securely in Firestore.
 * The Collection: A placeholder e-commerce section for "Artifacts of Introspection" (ready for future Firebase integration).
 * Community Sign-up: A functional form on The Threshold page to build a community mailing list via Firestore.
 * Support the Mission: A dedicated page for community contributions and financial support.
 * Cosmic Guides: Links to the separate cosmic_truths_guide.html file, providing educational content on Numerology and Astrology.
🛠️ Technology Stack
This is a single-page, multi-view application designed for maximum performance and simplicity.
 * Frontend: HTML5, Tailwind CSS (via CDN)
 * Styling: Custom CSS for metallic gold and Playfair Display/Inter fonts.
 * Functionality: Vanilla JavaScript
 * Database: Google Firebase/Firestore (for capturing Studio Inquiries and Community Sign-ups securely).
🚀 Deployment Instructions (GitHub Pages)
This project is built for easy, free hosting using GitHub Pages.
Required Files:
To publish, you must upload these two files to the root of this repository:
 * index.html (The main website file)
 * cosmic_truths_guide.html (The separate guide content file)
Step-by-Step Launch Guide:
 * Ensure Repository is Public: GitHub Pages requires the repository to be Public to host the website (Note: your database data remains private).
 * Upload Files: Use the "Add file" \rightarrow "Upload files" option to place both index.html and cosmic_truths_guide.html in the root of the repository.
 * Go to Pages: Click the Settings tab at the top, then select Pages on the left sidebar.
 * Set Source: Under "Build and deployment," ensure the Branch is set to main (or master) and the folder is set to / (root).
 * Save & Launch: Click Save. Your site will start building and will be live at the provided GitHub Pages URL in a few minutes!
📝 Future Development Notes
To fully launch the e-commerce section:
 * Integrate a real payment gateway (Stripe, Shopify, etc.).
 * Develop Firebase logic to manage product listings in The Collection dynamically.
