# opencpn_schema

# Building a schema for the validation of OpenCPN GPX files

The two files of the repo show a minimal OpenCPN GPX and the OpenCPN schema to validate that GPX. In addition the Topografix and Garmin schemas are referenced.

Development is being done locally using the Chrome web server extension. This explains the strange headers for the xsd and gpx files. 

When the schema goes live the xsd file will be hosted on the Internet. This will ensure that the GPX files created by OpenCPN contain valid xml.

Happy to accept pull requests with additions to the schema. This is a work in progress, so you can expect many additions to the xsd over the next few weeks. These will reference the tags already in use by OpenCPN.
