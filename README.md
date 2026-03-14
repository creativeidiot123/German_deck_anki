# German_deck_anki
Custom built from scratch german deck

# Download here
https://github.com/creativeidiot123/German_deck_anki/releases

# Flashcard Interaction Features

## Tinder-Style Swiping
- Swipe **right** → Cards you know
- Swipe **left** → Cards you failed
- Swipe **down** → Cards that were hard

---

## Color-Coded Visual Feedback
- 🟢 **Green overlay** → Correct (**Good**)
- 🔴 **Red overlay** → Wrong (**Again**)
- 🟡 **Yellow overlay** → **Hard**

---

## Satisfying Sounds & Haptics
- 🔊 **Success sound** when you get it right
- 🔊 **Failure sound** when you miss it
- 📳 **Vibration haptics**
  - Single pulse → Correct
  - Double pulse → Wrong
- 📳 Subtle vibration when revealing the answer

---

## Smart Time-Based Difficulty
- **< 7 seconds on a card**
  - Swipe right → **Good**
- **≥ 7 seconds**
  - Swipe right → Automatically marked as **Hard**

---

## Keyboard Shortcuts (PC Users)
- ⬇ **Arrow Down** → Hard  
- ⬅ **Arrow Left** → Again  
- ➡ **Arrow Right** → Good  
  - *(or Hard if you were slow)*

**Extra behavior**
- Press **any arrow key on the front card** → Flip the card


## Anki Settings to Use with This

Before using this template, adjust the following settings in Anki:

- Disable **any gestures** you currently use in Anki  
  - This template includes its **own gesture system** and handles all swipe interactions internally.

- Set **Card Zoom** to **80%**
  - Path: `Anki → Settings → Accessibility → Card Zoom`

- Enable **Fullscreen Mode**
  - Path: `Anki → Settings → Appearance`
  - Turn on **Hide System Bars**
  - Turn on **Hide Answer Buttons`

---

## Using This Template With Your Own Deck

To combine this template with your own deck:

1. Copy the following from **both templates**:
   - Front Template
   - Back Template
   - Styling (CSS)

2. Give both templates to ChatGPT.

3. Ask ChatGPT to:
   - Keep **your deck's field structure**
   - Apply **the UI and features from this template**
   - Generate a **final working template**.

---

## Manual Method (Faster)

You can also merge templates manually:

1. Open the **Front Template** and **Back Template** from this template.
2. Search for any fields written like:


   {{XXXX}}


3. Replace the field name inside with **your own deck’s field names**.

Example:


{{Front}}
{{Back}}
{{Hint}}


Replace with fields from your deck such as:


{{Question}}
{{Answer}}
{{Explanation}}


This keeps the **UI and logic intact** while adapting the template to your own deck.


