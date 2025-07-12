# passwordStrengthChecker
Overview
A simplistic, browser-based password strength checker that use only visual cues to indicate the strength of password.

Features  

Password strength logic:  

Strong: At least 10 characters, contains uppercase, lowercase, number, and special character.  

Moderate: At least 10 characters, but missing one or more required types.  

Weak: Less than 10 characters or missing most requirements.  

Visual feedback:  

Animated strength bar (red for Weak, yellow for Moderate, green for Strong).  

Bar glows with the corresponding color.  

Password input border and shadow match the strength color.

User interaction:

User enters a password and can only click the "Check" button to see the result.

File Structure

webfront.html: Main HTML file, includes the password input, strength bar, and button.

code.js: Contains the password strength checking logic and DOM manipulation for visual feedback.

style.css: Basic styling for layout, input, and button.

Passpng.png: Logo image displayed at the top of the checker.

Usage
Open webfront.html in any browser.

Enter a password and click "Check".

The strength bar and input border will visually indicate the password's strength.

