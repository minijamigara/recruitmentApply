# Vacancy Publish XML Hosting

This repository is used for hosting XML files related to job vacancies for performance testing of the LinkedIn Aggregator in the OrangeHRM system. The XML files in this repository can be accessed via GitHub Pages to simulate multiple instances publishing job vacancies.

## Purpose

The primary purpose of this repository is to:
- Host XML files that can be accessed via URLs.
- Facilitate performance testing by allowing the LinkedIn Aggregator to process large XML files.

## Hosted XML Files

The XML files in this repository are publicly accessible via GitHub Pages. Below are the available files:

| File Name      | URL                                                                 |
|----------------|---------------------------------------------------------------------|
| `client1.xml`  | [View client1.xml](https://minijamigara.github.io/recruitmentApply/client1.xml) |

## How to Use

1. **Access the XML File**:
   - Open the file URL in a web browser to view the XML content.
   - Example: [https://minijamigara.github.io/recruitmentApply/client1.xml](https://minijamigara.github.io/recruitmentApply/client1.xml)

2. **Test with LinkedIn Aggregator**:
   - Use the XML file URL in your Aggregator setup to simulate job vacancy data.
   - Ensure the Aggregator can parse and process the XML file.

## Setting Up GitHub Pages

To ensure the XML files are hosted correctly via GitHub Pages:

1. **Enable GitHub Pages**:
   - Go to the repository's **Settings**.
   - Scroll down to the **Pages** section.
   - In the **Source** dropdown, select `main` and click **Save**.

2. **Verify Deployment**:
   - After enabling GitHub Pages, GitHub will generate a URL for the hosted site.
   - You can view this URL in the **Pages** section of the repository settings.

3. **Access Hosted Files**:
   - The files in the repository can now be accessed using the URL format:
     ```
     https://<your-username>.github.io/<repository-name>/<file-name>.xml
     ```
   - For example:
     ```
     https://minijamigara.github.io/recruitmentApply/client1.xml
     ```

## Adding More XML Files

1. Create a new XML file and save it in the root directory of this repository.
2. Commit and push the file to the `main` branch.
3. Access the new file using the following format:
