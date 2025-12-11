# JavaFX Fortune Teller Application

## 💡 Overview
This project implements a fully functional GUI application in Java (utilizing JavaFX) that simulates a digital fortune teller. The application focuses on demonstrating proficient use of layout containers, event handling via buttons, and implementing application logic to ensure a dynamic, engaging user experience. 

## 🎯 Implementation Goals
This lab fulfills the following criteria:

* **Panel Structure:** Divide the GUI into three distinct panels (`Top`, `Middle`, `Bottom`) to manage layout and component placement effectively.
* **Event Handling:** Implement button functionality, utilizing a **Lambda Expression** for the `Quit` button as required.
* **Application Logic:** Ensure the generated fortunes never repeat the fortune immediately preceding it.

## 🛠️ GUI Layout Breakdown

### 1. Top Panel (Header)
* **Content:** Contains the title label and the fortune teller image.
* **Layout:** Components are centered horizontally.

### 2. Middle Panel (Content Display)
* **Content:** A `TextArea` wrapped in a `ScrollPane`.
* **Functionality:**
    * New fortunes are appended to the `TextArea`, displayed one per line.
    * **Core Logic:** The application prevents the generation of the exact same fortune as the last one displayed, ensuring variability.

### 3. Bottom Panel (Controls)
* **Content:** Two `Button` controls: "Get A Fortune" and "Quit."
* **Functionality:**
    * **"Get A Fortune" Button:** Triggers the fortune generation and display logic.
    * **"Quit" Button:** Closes the application. This action is implemented using a **Lambda Expression**.

## 🚀 Technical Features

* **Fortune List:** An array or list containing at least five distinct fortunes.
* **Random Generation:** Use the `Random` class to select fortunes, checking against a state variable to prevent immediate repetition.
* **Styling:** The overall layout is logically organized, ensuring centering and reasonable spacing for visual appeal.
