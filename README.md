This script uploads a file in multi parts into a patient template.

Needed steps:

1. Include file to be uploaded in the project or supply the full path to file.
2. Make sure the patient has a "File" object configured in the patient template. You must include it's JSON name in the FILE_KEY constant.
3. File part size cannot be smaller than 5MB, in such cases upload will fail with 409 client error