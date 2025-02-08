# Mad Libs Generator (Google Colab)

This Python script generates a Mad Libs story within a Google Colab environment. 

**Functionality:**

1. **Reads Story Template:** 
   - Reads a story template from a text file located in your Google Drive. 
   - The file path is currently set to `/content/drive/MyDrive/story-template.txt`. 
   - You can modify this path to match the actual location of your template file.

2. **Extracts Placeholders:**
   - Identifies and extracts placeholders within the story template. 
   - Placeholders are defined using angle brackets (`<>`), e.g., `<Noun>`, `<Adjective>`.

3. **Prompts User for Input:** 
   - Prompts the user to provide words for each placeholder.

4. **Generates Mad Libs Story:**
   - Replaces the placeholders in the story template with the user-provided words.
   - Prints the completed Mad Libs story to the console.

**To Use:**

1. **Upload Story Template:** Upload your story template file (in `.txt` format) to your Google Drive.
2. **Run in Colab:** 
   - Open this code in a Google Colab notebook.
   - Run the code.
   - Follow the prompts to enter words for each placeholder.
   - The completed Mad Libs story will be displayed in the Colab output.

**Note:**

* This script requires the `google.colab` library to be installed in the Colab environment.
* Ensure that the `story-template.txt` file is correctly uploaded to your Google Drive and the file path in the code is updated accordingly.

This README provides a basic overview of the code and instructions for its usage within the Google Colab environment.
