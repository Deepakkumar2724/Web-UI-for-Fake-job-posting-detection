
The **Job Scam Detector** features a modern, responsive, and intuitive user interface designed using **HTML**, **CSS**, and **JavaScript**. The UI ensures that users can easily interact with the system, paste job descriptions, and receive immediate feedback on the authenticity of the posting.

### 🧱 UI Components

#### 🔹 **Main Container**

* A centered card-style container with a dark, semi-transparent background.
* Styled with `border-radius`, `box-shadow`, and padding for visual appeal.
* Background image applied to the whole page for a professional look.

#### 🔹 **Header**

* Title: `Job Scam Detector` is prominently displayed using a vibrant cyan color.
* Subtitle: A brief prompt encouraging users to paste a job description.

#### 🔹 **Textarea Input**

* A multi-line text area for pasting job descriptions.
* Features:

  * Rounded borders
  * Highlighted border on focus (glow effect using `box-shadow`)
  * Responsive and mobile-friendly.
* Placeholder text guides users on what to enter.

#### 🔹 **Analyze Button**

* Styled with:

  * Cyan background
  * Bold black text
  * Rounded corners
  * Hover effects for interaction feedback
* Disabled state styling for better UX when input is missing.

#### 🔹 **Prediction Result Display**

* After submitting a job description, the result (`Real`, `Fake`, or `Error`) is displayed dynamically.
* Color-coded backgrounds for quick visual identification:

  * ✅ Green for **Real**
  * ❌ Red for **Fake**
  * ⚠️ Orange for **Errors**
* Uses conditional styling (based on prediction class) for readability and clarity.

#### 🔹 **Example Buttons**

* Two sample job postings provided:

  * **Legitimate Job**
  * **Fraudulent Job**
* Buttons auto-fill the textarea with example content when clicked.
* Styled to contrast with the dark background and remain clearly visible.

---

### 💡 User Experience (UX)

* **Minimalist Design**: Clean layout with clear focus on functionality.
* **Feedback Friendly**: Immediate, color-coded responses on analysis.
* **Interactive Examples**: Users can try built-in samples to understand how the system works before submitting their own content.
* **Mobile Friendly**: The design adapts well to different screen sizes using `viewport` settings and fluid container widths.

---
