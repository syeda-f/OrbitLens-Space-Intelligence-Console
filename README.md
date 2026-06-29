# OrbitLens-Space-Intelligence-Console
OrbitLens is a web app that turns dry technical satellite log PDFs into interactive space mission dashboards.

## What It Does
**Document Panel (left sidebar)**: Here, you can upload one or more PDF telemetry logs. OrbitLens extracts the text automatically and lists it in a sidebar. Click any document to make it active, and the dashboard and chat will use it as context.

**Main Viewer (center)**: Switch between two views using the tabs at the top:
+ **Dashboard** shows KPI cards for key metrics extracted from the log (voltage, temperature, pressure, cycle count, system status), plus four charts: a thermal trajectory line chart, a threshold analysis bar chart, a resource load doughnut chart, and a subsystem efficiency radar chart. Each chart includes an auto-generated insight caption.
+ **PDF View** — renders the raw PDF so you can read through the original document page by page.
  
**AI Chat (right panel)**: Can ask questions about the loaded documents in plain language. The chat uses Google Gemini under the hood. You can switch between two agent modes:
+ Engineer: technical, detailed answers, treats you like a propulsion engineer
+ Specialist: cleaner, more concise answers for general analysis

**Ambient Audio**: Three synthesized sounds that you can toggle on/off: Deep Space, Nebula Hum, and Pulse Grid.

## How To Get Started 
+ Download or clone this repo
+ Open orbitlens.html in any modern browser (Brave recommended)
+ Get a Google Gemini API key (it's free)
+ Paste your API key into the input field in the top right corner. The status dot turns green when it's connected
+ Click Upload Telemetry and select a PDF log file
+ Explore the Dashboard and PDF views, then ask questions in the chat

## Tech Stack
PDF.js, Chart.js, Tone.js, marked.j, Google Gemini API, Google Fonts

