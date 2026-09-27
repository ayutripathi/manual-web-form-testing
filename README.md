# Manual Web Form Testing

## 📌 Project Overview

This project demonstrates hands-on manual testing of a web-based practice form.

The objective was to practice the complete basic QA workflow:

- Understanding the application
- Identifying test scenarios
- Designing test cases
- Executing test cases
- Recording actual results
- Identifying unexpected behaviour
- Documenting observations

## 🌐 Application Tested

A practice web form containing:

- Name input field
- Dropdown/select field
- Multiple checkboxes
- Date/DOB field
- Submit button

## 🧪 Testing Scope

The following areas were tested:

### Input Field Testing
- Valid text input
- Numeric input
- Empty input
- Input behaviour and acceptance

### Dropdown Testing
- Selecting different options
- Submitting with a selected option
- Observing selection behaviour after submission

### Checkbox Testing
- Selecting individual checkboxes
- Unselecting checkboxes
- Selecting multiple checkboxes
- Selecting all available checkboxes

### Date Field Testing
- Selecting a valid date
- Selecting DOB through the date picker
- Date picker navigation
- Attempting invalid text input
- Observing date field behaviour

### Form Submission Testing
- Submitting with valid data
- Submitting with all fields empty
- Submitting with partially completed fields
- Observing success messages
- Observing page refresh behaviour

## 📊 Test Execution

A total of **11 test scenarios/cases** were executed during the testing session.

The complete execution details are available in:

`Test-Cases/Project_1_Test_Cases_and_Execution.xlsx`

The spreadsheet contains:

- Test Case ID
- Scenario
- Preconditions
- Steps
- Test Data
- Expected Result
- Actual Result
- Status

## 🔎 Findings & Observations

The following behaviours were observed during testing:

### Observation 1 — Empty Form Submission

The form displayed a success message when submitted with all fields empty.

### Observation 2 — Partial Form Submission

The form displayed a success message when only the Name field was filled and the remaining fields were left empty/default.

### Observation 3 — Numeric Input in Name Field

The Name field accepted the numeric value:

`123456`

These findings are documented as **observations rather than confirmed defects** because no formal requirements specification was provided for the practice application.

Detailed documentation is available in:

`Bug-Reports/Project_1_Observation_and_Defect_Report.docx`

## ✅ Positive Test Findings

The following behaviours worked successfully during testing:

- Dropdown selection worked.
- Checkboxes could be selected and unselected.
- Multiple checkboxes could be selected simultaneously.
- A valid DOB could be selected through the date picker.
- Alphabetic input could not be entered into the date field.
- Form submission produced a response message.

## 🛠️ Testing Approach

The project used a hands-on manual testing approach involving:

1. Exploratory observation of the application's controls.
2. Identification of possible test scenarios.
3. Test case creation.
4. Manual execution.
5. Recording actual application behaviour.
6. Documentation of unexpected or noteworthy observations.

## ⚠️ Project Limitation

No formal requirements or requirement specification was provided with the practice application.

Therefore, expected behaviour was not assumed to be a confirmed product requirement. Where requirements were unavailable, the observed behaviour was documented as an observation rather than automatically classified as a defect.

## 📚 Key Learnings

Through this project, I practiced:

- Writing test cases
- Designing positive and negative test scenarios
- Testing form controls
- Validating user input behaviour
- Executing test cases manually
- Recording actual results
- Distinguishing observations from confirmed defects
- Writing basic defect/observation reports
- Organizing QA testing documentation

## 📁 Project Structure

```text
manual-web-form-testing/
│
├── README.md
│
├── Test-Cases/
│   └── Project_1_Test_Cases_and_Execution.xlsx
│
├── Bug-Reports/
│   └── Project_1_Observation_and_Defect_Report.docx
│
└── Evidence/
    └── screenshots/
