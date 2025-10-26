# Basic Web Automation - Fill a Web Form

## Aim:
To develop a UiPath automation that opens a web page containing a contact form, fills in user details automatically, and submits the form.

## Procedure:
### Step 1: Create a New Project
* Open UiPath Studio → Click Process → Create.
### Step 2: Use ‘Open Browser’ Activity
* Drag the Open Browser activity from the Activities panel.
* In the URL field, enter the website link of the contact form.
  - Example: "https://forms.gle/CP8d41DffGeRGAHQ7"
* Choose the browser type (e.g., Chrome or Edge).
### Step 3: Enter User Data
* Drag and drop the following activities inside the Do container of the Open Browser activity:
* Use "Type Into" activity to enter the data
(Use the ‘Indicate on Screen’ option to select each form field.)
### Step 4: Click Submit Button
* Drag a Click activity.
* Use Indicate on Screen to select the Submit button.
### Step 5: Save and Run
* Save the workflow.
* Click Run to execute.
* UiPath will open the website, fill in all fields automatically, and submit the form.

### WORKFLOW:
<img width="1919" height="1079" alt="Screenshot 2025-10-26 111407" src="https://github.com/user-attachments/assets/0c2e68c4-8929-4b9e-bfc9-352cd410b7de" />
<img width="1919" height="1079" alt="Screenshot 2025-10-26 111421" src="https://github.com/user-attachments/assets/7a39281b-0d92-4751-8df8-69a1d81370b4" />
<img width="1919" height="1079" alt="Screenshot 2025-10-26 111427" src="https://github.com/user-attachments/assets/a3a50c5f-4f5d-49bb-8f7a-fa7570a3a216" />

## Output:
These are the Responses that is automatically filled using automation:

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/cd313c7d-a159-45b3-99be-9b34d84ef893" />

## Result:
The automation successfully opens the web form, inputs user details such as name, email, country, and clicks the submit button automatically. The process completes without manual intervention, demonstrating how UiPath can automate web-based form submissions efficiently.


