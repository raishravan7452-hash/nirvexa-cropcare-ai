# nirvexa-cropcare-ai
AI POWERED CROP DISEASE DETECTION APP FOR OUR COASTAL FARMERS GROWING ARECANUT,COCONUT AND CASHEW ,WITH VOICE ASSISTANT AND MULTILINGUAL SUPPORT INCLUDING TULU,KANNADA,ENGLISH,HINDI AND MALAYALAM
CropCare AI
AI-powered crop disease detection for arecanut,
coconut and cashew farmers, with a voice assistant
and multilingual support (Tulu, Kannada, English,
Hindi, Malayalam).
Team Nirvexa | Open Innovation Hackathon,
Vivekananda College of Engineering and Technology,
Puttur
Shravan Rai (Team Leader)
Skanda R Shetty
Suchit R Kotian

Problem
Farmers in the Puttur region lose a large share of their
yield to diseases such as arecanut Koleroga and
coconut bud rot. These are often spotted late
because experts and agri-labs are far away.

Solution
The farmer clicks a photo of the affected leaf, fruit or
stem. The app identifies the disease in seconds,

shows a confidence score and suggests a remedy. It
can read the remedy aloud and works in the farmer's
own language, including Tulu.
Features
Photo-based disease diagnosis (arecanut
Koleroga, coconut bud rot, cashew anthracnose)
Voice assistant: speak symptoms and hear the
remedy read aloud
Language switch: Tulu, Kannada, English, Hindi,
Malayalam
Diagnosis history and a nearby-cases card

Current status
This repository contains a working prototype. The
diagnosis is simulated and no trained model is
connected yet. Remedies shown are general
guidance, so farmers should confirm doses with their
local Krishi Vigyan Kendra.

Run the prototype
1. Download or clone this repository.
2. Open index.html in Google Chrome (laptop or
Android phone). No installation is needed.

3. Pick a language, then tap Check disease to
upload or take a leaf photo, or tap Try a sample.
4. Tap Read aloud to hear the remedy. Tap Speak
symptoms for voice input (needs internet and
Chrome).

Notes
Voice input works best in Chrome on Android.
Browsers have no Tulu voice, so Tulu text is read
aloud with a Kannada voice.
Photos are not stored. Scan history is saved only
in your own browser.

Planned tech stack

Layer Technology
App Flutter (Android)

Layer Technology
AI
model

TensorFlow, MobileNetV3, TensorFlow
Lite

Voice

Android Speech-to-Text and Text-to-
Speech

Backend FastAPI, PostgreSQL, Firebase
Data

PlantVillage, Kaggle datasets, local
arecanut and coconut photos

Roadmap
[x] Multilingual prototype with voice and history
[ ] Collect and label local disease images
[ ] Train and export the on-device model
[ ] Build the Flutter app and backend API
[ ] Outbreak map for extension officers
[ ] Field testing with farmers in Dakshina Kannada

License
MIT see LICENSE.
