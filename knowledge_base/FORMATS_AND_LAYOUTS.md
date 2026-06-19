# 📐 Formats & Layout Rules

**Objective:** This document dictates how the AI must adapt the visual composition based on the required aspect ratio. The layout must respect UI safe zones depending on the platform.

### 🖥️ 16:9 Landscape (YouTube / Web)
When generating prompts for horizontal video:
* **Keywords:** You must include `16:9 wide landscape composition` at the start, and `Format: 16:9 landscape` at the end of the prompt.
* **Composition:** `Flat lay composition` is highly recommended. Spread secondary elements horizontally.
* **Layout Rules:** The main physical object sits in the center. The blue organic brushstroke (#3B7DD8) should flow horizontally behind the object. 
* **Text Placement:** EXO fonts have plenty of room to breathe at the top or spanning across the width.

### 📱 9:16 Portrait (TikTok / Reels / Shorts)
When generating prompts for vertical video:
* **Keywords:** You must include `9:16 vertical portrait composition` at the start, and `Format: 9:16 portrait` at the end of the prompt.
* **Composition:** `Centered product composition` is highly recommended. The layout must be strictly vertical.
* **UI Safe Zones (CRITICAL):** 
  * The bottom 30% is covered by captions and descriptions.
  * The right edge is covered by Like/Comment buttons.
  * **Rule:** Force the main physical object to be dead center. Keep doodles tightly wrapped around the object.
* **Text Placement:** The Large EXO BOLD Heading and EXO REGULAR Subheading MUST be placed strictly in the top 20% of the canvas (Top Safe Zone).

**Rule for Both Formats:** The aesthetic (`mixed media collage... zine editorial aesthetic`) and the Negative Prompt remain identical regardless of the format.
