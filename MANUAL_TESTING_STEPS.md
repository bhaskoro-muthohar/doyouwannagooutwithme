# Manual Testing Steps

This document outlines the manual testing steps for the "Do you wanna go out with me?" website enhancements.

## 1. "No" Button Functionality (on `index.html`)

**Objective:** Verify the "No" button's movement and page behavior.

**Test Steps:**

1.  Open `index.html` in a web browser.
2.  **Hover Test:**
    a.  Move the mouse cursor over the "No" button.
    b.  Observe the button's movement. It should smoothly slide to a new random position on the page.
    c.  Repeat steps 2a-2b multiple times (e.g., 5-10 times).
    d.  **Expected Result:** The "No" button consistently moves to a new random position smoothly each time the cursor hovers over it.
    e.  **Expected Result:** The browser window should not display any scrollbars, even if the button moves towards the edges of the viewport.
3.  **Click Test:**
    a.  Attempt to click the "No" button.
    b.  Observe the button's movement. It should smoothly slide to a new random position on the page upon clicking (or attempting to click, as it moves on hover too).
    c.  Repeat steps 3a-3b multiple times (e.g., 5-10 times).
    d.  **Expected Result:** The "No" button consistently moves to a new random position smoothly each time it is clicked or hovered over during the click attempt.

## 2. "No" Button Taunts (on `index.html`)

**Objective:** Verify the appearance, content, and animation of taunt messages when interacting with the "No" button.

**Test Steps:**

1.  Open `index.html` in a web browser.
2.  Interact with the "No" button by either hovering over it or clicking it.
3.  **Taunt Message Appearance:**
    a.  **Expected Result:** A text message appears in a styled box (speech bubble appearance: white background, pink text, rounded corners, shadow, pink border).
4.  **Taunt Message Content:**
    a.  Observe the text content of the message.
    b.  **Expected Result:** The message displayed is one of the following: "Too slow!", "Try again!", "Haha!", "Can't catch me!", or "Missed me!".
    c.  Repeat step 2 multiple times to see different messages.
    d.  **Expected Result:** Different taunts from the predefined list are shown randomly.
5.  **Taunt Message Positioning:**
    a.  Observe the position of the taunt message on the screen.
    b.  **Expected Result:** The taunt message appears at a fixed position: horizontally centered and near the top of the page (specifically, `top: 20%`).
6.  **Taunt Message Disappearance & Animation:**
    a.  Observe the taunt message after it appears.
    b.  **Expected Result:** The taunt message automatically disappears after approximately 1.75 seconds.
    c.  **Expected Result:** The taunt message displays a "fadeInOut" animation: it should fade in and scale up when appearing, and fade out and scale down when disappearing.

## 3. "Yes" Button Functionality (on `index.html`)

**Objective:** Verify that the "Yes" button correctly navigates to the `yes.html` page.

**Test Steps:**

1.  Open `index.html` in a web browser.
2.  Locate and click the "Yes" button.
3.  **Expected Result:** The browser navigates to the `yes.html` page. The URL in the address bar should change to reflect this.

## 4. "Yes" Page Enhancements (on `yes.html`)

**Objective:** Verify the updated heading text and its animation, and the presence of the GIF on the `yes.html` page.

**Test Steps:**

1.  Navigate to `yes.html` (e.g., by clicking the "Yes" button on `index.html`).
2.  **Heading Text Content:**
    a.  Observe the main heading text on the page.
    b.  **Expected Result:** The heading text should read "Woohoo! Get ready for an awesome time!".
3.  **Heading Text Animation:**
    a.  Observe the heading text as soon as the `yes.html` page loads.
    b.  **Expected Result:** The heading text should animate in with a "Fade-in and Scale-up" effect. It should start slightly smaller and transparent, then grow to its normal size and full opacity over approximately 1 second.
4.  **GIF Visibility:**
    a.  Look for the GIF image on the page.
    b.  **Expected Result:** The GIF (cute animated illustration, e.g., bears hugging) is visible and correctly loaded below the heading.

---
End of Manual Testing Steps.
