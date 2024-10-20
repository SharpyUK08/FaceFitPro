FaceFitPro - User Guide
=======================

Version 1.0

Introduction
------------

FaceFitPro is an application designed to assist with conducting face fit tests for respiratory protective equipment (RPE). It guides you through the test process, records results, and generates a comprehensive report.

This guide will help you understand how to use the application, adjust settings, and create your own custom templates for reports.

Table of Contents
-----------------

1. Getting Started
2. Conducting a Face Fit Test
3. Adjusting Settings
4. Creating Custom Templates
5. Support and Feedback
6. Acknowledgments

Getting Started
---------------

### Launching the Application

- Open the FaceFitPro application.
- You will be greeted with the **Main Menu**.

### Main Menu Options

- **Start Test**: Begin a new face fit test.
- **Settings**: Adjust application settings and preferences.
- **Help**: Access this user guide.
- **Exit**: Close the application.

Conducting a Face Fit Test
--------------------------

### 1. Starting a New Test

- Click on **Start Test** from the Main Menu.
- You will be taken to the **Test Subject Information** tab.

### 2. Entering Test Subject Information

- Fill in the required details:
  - **Name**
  - **Employee ID**
  - **Department**
  - **Tester Name**
  - **Mask Make**
  - **Mask Model**
  - **Mask Size**
  - **PPE Details**
- Click on **Proceed to Sensitivity Test**.

### 3. Sensitivity Test

- Follow the instructions to perform the sensitivity test.
- Determine the **Sensitivity Band** based on the number of sprays it takes for the subject to taste the solution.
  - **Band 1**: Up to 10 sprays.
  - **Band 2**: Up to 20 sprays.
  - **Band 3**: Up to 30 sprays.
- Enter the Sensitivity Band when prompted.
- The application will inform you of the initial sprays and sprays needed every 30 seconds during the test.

### 4. Conducting the Fit Test

- The application will guide you through the exercises:
  - **Normal Breathing**
  - **Deep Breathing**
  - **Head Side to Side**
  - **Head Up and Down**
  - **Talking** (Rainbow Passage)
  - **Bending Over**
  - **Final Normal Breathing**
- Each exercise lasts **60 seconds**.
- The **progress bar** indicates the time remaining.
- **Spray Reminders**:
  - Apply the specified number of sprays every 30 seconds as reminded.
  - An audio cue and visual reminder will alert you.
- If the test subject detects the test solution at any point:
  - Click **Fail Test**.
- If the subject does not detect the solution:
  - The test will proceed automatically.

### 5. Reveal Test

- After the exercises, perform the **Reveal Test** to confirm the subject can detect the solution.
- Instruct the subject to slightly lift the mask within the hood.
- Confirm if the subject can taste the solution.
- Click **Pass** or **Fail** accordingly.

### 6. Viewing Results

- The application will display the **Results** of the test.
- Review the information to ensure all details are correct.

### 7. Generating the Report

- Click on **Generate Report** to create a PDF report of the test.
- The report will be saved in the specified **Report Directory**.
- You will be prompted to open the folder containing the report.

Adjusting Settings
------------------

### Accessing Settings

- Click on **Settings** from the Main Menu.

### Template File

- The template file is used to generate the PDF report.
- The default template is **FFCERTPY.docx**.
- To use a custom template:
  - Click **Browse** next to **Template File**.
  - Select your custom template file (.docx format).
  - Ensure your template contains the correct merge fields (see [Creating Custom Templates](#creating-custom-templates)).

### Report Directory

- Specify the folder where generated reports will be saved.
- Click **Browse** next to **Report Directory** to select a folder.

### Saving Settings

- After making changes, click on **Save Settings**.
- Your preferences will be saved for future sessions.

### Licenses

- Click on **Licenses** to view the software licenses and acknowledgments.

Creating Custom Templates
-------------------------

You can create your own Word document templates to customize the appearance of the generated reports.

### 1. Creating a Template

- Open **Microsoft Word** or **LibreOffice Writer**.
- Design your report layout as desired.
- Use placeholders for data fields using the following format:
  - Double angle brackets: `«FieldName»`
  - Example: `«Name»`, `«Department»`, `«Date_of_Test»`

### 2. Available Field Names

- The following field names can be used in your template:

Name
Employee_ID
Department
Tester_Name
Mask_Make
Mask_Model
Mask_Size
PPE_Details
Date_of_Test
Next_Test_Due
Clean_Shaven
Medically_Fit
Not_Smoked_Eaten
Visual_Check
Donning
Pre_Use_Fit_Check
Band_1_Tick
Band_2_Tick
Band_3_Tick
Normal_Breathing
Deep_Breathing
Head_Side_To_Side
Head_Up_and_Down
Talking
Bending_Over
Final_Normal_Breathing
Reveal_Test_Result
Overall_Pass

### 3. Saving the Template

- Save your template as a `.docx` file.
- In the application, go to **Settings** and select your new template file.

### 4. Notes

- **Field names are case-sensitive** and must match exactly.
- Ensure that all placeholders in your template correspond to valid field names.
- Use appropriate formatting and layout to enhance the appearance of your reports.

Support and Feedback
--------------------

If you encounter any issues or have suggestions for improvement, please contact:

**Developer**: Sam Sharpe

**Website**: [www.iamsamsharpe.com](https://www.iamsamsharpe.com)

Acknowledgments
---------------

Thank you for using FaceFitPro to assist with your face fit testing needs.
