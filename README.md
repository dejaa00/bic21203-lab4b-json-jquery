# BIC21203 Web Development — Lab #4b: Client-Side Scripting (JSON and jQuery)

## Student Details
- **Name:** SITI NUR KHADIJAH BINTI MOHAMAD ALAWI
- **Matric Number:** AI250057
- **Course:** BIC21203 Web Development (Session 2026/2027)

## Project Overview
This repository contains the solutions for Lab #4b, demonstrating valid JSON dataset creation, asynchronous data retrieval using the native `fetch()` API, and DOM manipulation and event handling using jQuery 4.0.0.

## Files Included
- `books.json` — Structured JSON dataset containing a top-level `books` array with two book objects.
- `books.html` — Fetches and displays selected book details (`title`, `author`, and `genres`) safely using `textContent` and `createElement()`.
- `jquery-dom.html` — Demonstrates jQuery equivalents (`.text()`, `.addClass()`, `.on("click", ...)`) for native JavaScript DOM operations.

## Setup & How to Run
1. Clone or download this repository to your local machine.
2. Open the project folder in **VS Code**.
3. Install the **Live Server** extension (required because browsers block `fetch()` requests to local JSON files over `file://`).
4. Right-click `books.html` and select **Open with Live Server** to view the fetched JSON data.
5. Open `jquery-dom.html` in a modern browser (or via Live Server) and click **Click me** to test the jQuery DOM updates and alert event.

## Output Screenshots

### Question 1: Create and Structure JSON Data (`books.json`)
<img width="1366" height="724" alt="image" src="https://github.com/user-attachments/assets/c3912d0e-3bb4-4b45-abb4-c02b64e544e1" />


### Question 2: Retrieve and Display JSON Data (`books.html`)
<img width="1366" height="727" alt="image" src="https://github.com/user-attachments/assets/db69c194-e2dd-4c04-b3b2-7ec789e238bf" />


### Question 3: Compare Native JavaScript and jQuery (`jquery-dom.html`)
**Page output after jQuery DOM updates:**
<img width="1366" height="727" alt="image" src="https://github.com/user-attachments/assets/2407a6a5-c62e-4d9b-b9b3-a03fcaef1d79" />


**Alert popup after clicking button:**
<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/c8e795d7-b227-4314-98ef-7d324b431005" />
