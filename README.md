# InDesign a keyboard shortcut set and tempplate for pretty printing keyboard shortcut sets 
A set of shortcuts plus a remplate for pretty printing the entire list which InDesign exports as txt.

Preview:

<img width="433" alt="Screenshot 2024-08-23 at 4 30 38 pm" src="https://github.com/user-attachments/assets/88fe06ac-73bb-4611-b9f4-c3924119fea0">


## Steps to pretty print your own set
1.  Export the set from InDsign Keyboard Shortcuts window… click on "Show set…" button

<img width="862" alt="Screenshot 2024-08-23 at 2 39 33 pm" src="https://github.com/user-attachments/assets/7d7c313c-a4b4-4753-8ead-55ce7a8d1b27">

2.  Open the template file in InDesign.

3.  **Select all** text in the shortcut text file generated by InDesign, copy and paste it into the InDesign template document (replacing the old text).

4.  **Select all** text and set to **"1.  Head"** para style using the Paragraph styles palete.

5.  Open InDesign's **Find and Replace** window, goto the second tab, **GREP**.

6.  Enter **^\t.$** **in the 'find what' field   <- this finds all the lines begining in tabs using GREP codes

7.  Enter "**0. Body**" Paragraph style in the **Change format** field.

8.  Click "**Replace all**" button to change the style of all lines starting in a tab

   <img width="524" alt="Screenshot 2024-08-23 at 3 51 43 pm" src="https://github.com/user-attachments/assets/8cff783d-90fd-4611-a486-0174492290f3">
