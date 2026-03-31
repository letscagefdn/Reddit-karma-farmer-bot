# Reddit Karma Builder

Standard automation gets your account flagged because it interacts with the DOM and moves with mathematical precision. This tool bypasses those traps by using computer vision to navigate Reddit exactly as a human would.

## The Problem with Traditional Scraping

Most Reddit bots use Selenium or Puppeteer to find buttons via HTML tags. Reddit detects this instantly. They monitor for:

* **Injected JavaScript hooks:** Scripts that leave footprints in the browser environment.
* **Instantaneous cursor "teleportation":** Moving to the exact center of elements in zero time.
* **Non-human typing speeds:** Perfect rhythm that lacks the variance of physical keystrokes.
* **Direct API calls:** Patterns that don't match standard browser behavior.

If your bot clicks a reply button in 12 milliseconds every time, the account is burned before it starts.

## How This System Evades Detection

Instead of reading code, this tool reads the screen.

### YOLO AI Vision Integration
The bot uses a trained YOLO (You Only Look Once) model to visually identify UI elements. It sees the "Reply" button, the text field, and the upvote icons as pixels, not as lines of code. It does not interact with the underlying HTML, meaning there are no automated footprints for Reddit's scripts to find.

### Ghost-Level Cursor Movements
Clicks are never static. The system calculates curved paths with randomized acceleration and slight offsets. It mimics the natural tremor and imperfect navigation of a physical mouse.

### CDP-Based Stealth
By utilizing the Chrome DevTools Protocol (CDP) rather than standard WebDriver protocols, the bot eliminates the `navigator.webdriver` flag and other common automation signals. 

### Contextual Natural Language
The bot avoids generic spam. It analyzes thread content to generate responses that contribute to the conversation, increasing the likelihood of organic upvotes from real users.

---

## Installation

1. **Go to Karmabuilder.xyz:**
   [Karma Builder](https://karmabuilder.xyz)
