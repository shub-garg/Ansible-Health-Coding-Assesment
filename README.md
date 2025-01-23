# Ansible-Health-Coding-Assessment

## Google Docs Markdown Parser

This Python script is designed to run in a Google Colab environment. It takes markdown meeting notes as input and programmatically creates a well-formatted Google Doc using the Google Docs API.

Output Document [https://docs.google.com/document/d/19q4GwU5_cVfZehy8tkDbaYt6w_n62458Mf5a-orxgJU/edit?usp=sharing](https://docs.google.com/document/d/19q4GwU5_cVfZehy8tkDbaYt6w_n62458Mf5a-orxgJU/edit?usp=sharing)

### Features
- Parses markdown meeting notes and applies proper formatting in Google Docs.
- Supports:
  - Headings (Heading 1, Heading 2, Heading 3 styles)
  - Nested bullet points with indentation
  - Google Docs checkboxes for markdown checkboxes
  - Assignee mentions with distinct styling
  - Footer information with italic and light gray styling

### Requirements
- Python 3.x
- Google Colab environment

### Dependencies
Install the following Python libraries:
- `googleapiclient`
- `google.auth`

## How to Enable Google Docs API
To use this script, you need to enable the Google Docs API for your account. Follow these steps:

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project or select an existing one.
3. Navigate to the **API & Services > Library** section.
4. Search for "Google Docs API" and click on it.
5. Click the **Enable** button.

### Setup Instructions
1. **Clone or Download the Repository**:
   ```
   git clone https://github.com/shub-garg/Ansible-Health-Coding-Assessment.git
   cd Ansible-Health-Coding-Assessment
   ```
   
2. **Upload to Google Colab**:
Open the `.ipynb` file in Google Colab.

4. **Authenticate with Google Docs API**:
The script will prompt you to authenticate. Follow the on-screen instructions to grant permissions.

5. **Run the Script**:
Simply execute all cells in the Colab notebook to generate a new Google Doc.


### Example Input
Markdown meeting notes:
```markdown
# Product Team Sync - May 15, 2023

## Attendees
- Sarah Chen (Product Lead)
- Mike Johnson (Engineering)
- Anna Smith (Design)
- David Park (QA)

## Agenda
- [ ] @sarah: Finalize Q3 roadmap by Friday
```

### Output
A formatted Google Doc with headings, bullet points, checkboxes, and styled mentions. Please follow the link for the [output document](https://docs.google.com/document/d/19q4GwU5_cVfZehy8tkDbaYt6w_n62458Mf5a-orxgJU/edit?usp=sharing).

### Troubleshooting
If you encounter errors:

 - Ensure Google Docs API is enabled for your account.
 - Re-authenticate if needed.
 - Verify markdown input formatting.

### License
This project is licensed under the MIT License.


---
