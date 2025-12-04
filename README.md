🌿 WildSentinel AI: Intelligent Animal Intrusion Detection

Smarter Alerts. Safer Crops. > An automated, real-time AI surveillance system designed to mitigate human-wildlife conflict by detecting dangerous predators and sending instant alerts.

🌟 Inspiration

Human–wildlife conflict is a growing issue across farms and rural areas. Farmers lose crops, and both humans and animals face danger. Existing solutions like electric fences are expensive or harmful.

WildSentinel AI was born to become a digital guardian—an affordable, browser-based solution that turns any laptop or phone into a smart security camera that spots predators like Lions, Tigers, and Elephants before damage happens.

🚀 Features

🦁 Hypersensitive Detection: Uses a Hybrid AI approach to detect specific threats like Lions, Tigers, Leopards, Boars, and Elephants with high accuracy.

⚠️ Threat Classification: Automatically sorts detected objects into "Harmful" (Predators) and "Harmless" (Livestock/Pets) categories.

📲 Instant WhatsApp Alerts: Automatically triggers a WhatsApp message with the intruder details and timestamp upon detection.

📸 Auto-Evidence Capture: Automatically takes a snapshot of the intruder and downloads it to the device for record-keeping.

🛡️ Edge Computing: Runs 100% locally in the browser. No video data is sent to the cloud, ensuring privacy and low latency.

🔊 Audio Warnings: Uses Text-to-Speech to announce threats verbally.

🛠️ Tech Stack

Frontend: HTML5, Tailwind CSS (for reactive UI).

AI Engine:  TensorFlow.js.

COCO-SSD: For object localization (bounding boxes).

MobileNet V2: For detailed species classification (Deep Scanning).

Logic: Custom "Hybrid AI" algorithm (Double-checks detection confidence against species classification).

APIs: Web Share API, MediaDevices API, Canvas API.

⚙️ How It Works (The Hybrid Logic)

Standard object detectors often mistake wild animals for dogs or cats. WildSentinel solves this with a Dual-Engine approach:

Scanner (COCO-SSD): Scans the frame for any movement or animal shape.

Verifier (MobileNet): If an animal is found, the system crops that area and runs a deep classification scan.

Cross-Check: If the Verifier detects a "Tiger" with >5% confidence, it overrides the Scanner and triggers a Red Alert, even if the Scanner thought it was just a "Cat".

Webpage Link: https://satheesh1929.github.io/Wild-Animal-Detection/
