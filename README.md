Google Play Services Lib
=====================

Google Play Services library necessary for using the Google Drive API.
This library is required by the Google Drive Uploader project.

This can be used by any Android project to use the API's provided
by Google Play services.

There is technically no source, but the src folder is necessary
to ensure that the build system works. The content is actually
located in the libs/ directory.

USAGE:

Make sure you import this Android library project into your IDE
and set this project as a dependency.

Note that if you use proguard, you will want to include the
options from proguard.txt in your configuration.