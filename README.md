# Ansible-Health-Coding-Assesment

## Google Docs Markdown Parser

This Python script is designed to run in a Google Colab environment. It takes markdown meeting notes as input and programmatically creates a well-formatted Google Doc using the Google Docs API.

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

### Setup Instructions
1. **Clone or Download the Repository**:
   ```
   git clone https://github.com/yourusername/google-docs-markdown-parser.git
   cd google-docs-markdown-parser
   ```
2. **Upload to Google Colab**:
Open the `.ipynb` file in Google Colab.

3. **Authenticate with Google Docs API**:
The script will prompt you to authenticate. Follow the on-screen instructions to grant permissions.

4. **Run the Script**:
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

### Example Output
A formatted Google Doc with headings, bullet points, checkboxes, and styled mentions.

### Troubleshooting
If you encounter errors:

 - Ensure Google Docs API is enabled for your account.
 - Re-authenticate if needed.
 - Verify markdown input formatting.

### License
This project is licensed under the MIT License.
