## Bug Report — CIEE One Rio

📅 Report Date: 04/24/2025 

🖥️ Platform: Mobile

📍 Bug Location: "Diversity" section
![Imagens](https://github.com/Pedr0-Raposo/Portfolio_QA/blob/main/Bugs%20Relatados/imagens/CIEELocal.jpg)

📝 Descrição: 
When the user selects "Yes" to the question about using a "Social Name" and enters a name, then changes the answer to "No" without manually clearing the field, the system prevents progression to the next step.
The form retains the previously entered name, causing a validation error, even though the "No" option is selected — when it should ignore any input.

## 🔄 Steps to Reproduce

Step 1: Access the "Diversity" section.

Step 2: Select "Yes" and enter any text into the "Social Name" field.

Step 3: Switch the selection to "No" without clearing the entered text.

Step 4: Attempt to proceed by clicking "Save."

## 🎯 Expected Result
When selecting "No," the "Social Name" field should be automatically cleared or ignored, allowing the user to proceed without validation issues.


## 🚨 Actual Result
The "Social Name" field retains the entered text even after switching the selection to "No."

The system still requires the field to be empty or valid, preventing the user from proceeding.

## ⚠ Bug Impact
🔸 Moderate: The bug blocks the completion of a form step unless the user figures out a workaround (switching back to "Yes," clearing the field, and then selecting "No").

## 🛠 Possible Solution
Normally, when the user switches to "No," the system should:

Automatically clear the "Social Name" field, resetting its content.

Remove any validation linked to that field.

Update the internal state to reflect that the social name is no longer relevant.

## 🖼️ Screenshot / Video 

![Imagens](https://github.com/Pedr0-Raposo/Portfolio_QA/blob/main/Bugs%20Relatados/imagens/CIEE.jpg)





