# Viral-POV-Videos
AI Workflow to Create Viral POV Videos—Fully Automated


Excited to share a creative automation project I worked on today using n8n, Google Sheets, OpenAI, Piapi.ai (Flux Model), and Runway—a system that produces short-form POV videos similar to the ones that go viral on Instagram Reels and YouTube Shorts.

This system is designed for businesses and creators looking to scale fast-paced content marketing with minimal effort.

Here’s how it works:

1️⃣ Start with an Idea
Short video concepts are stored in a Google Sheet(often a single line). The workflow pulls approved ideas automatically.

2️⃣ Generate a Scripted Prompt with AI
An AI agent powered by OpenAI transforms each one-line idea into a rich, cinematic first-person POV prompt—designed to be immersive and visually engaging.

3️⃣ Create High-Quality Visuals
The prompt is passed to the Flux text-to-image model via PyAPI, generating visuals optimized for video.

4️⃣ Produce Short-form Videos
Using RunwayML, the still images are animated into high-resolution first-person POV videos, complete with a cinematic feel.

5️⃣ Track Results
The system updates the original Google Sheet with links to the generated image and video assets—keeping everything organized and ready for upload.

🔁 All of this is fully automated and scalable with n8n.

This kind of system is ideal for businesses and creators aiming to produce consistent, eye-catching content without manual design work.

