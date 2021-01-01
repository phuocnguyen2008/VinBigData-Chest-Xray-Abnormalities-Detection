# DICOM file format
Every DICOM file holds patient information such as name, DoB, sex, ID. Each DICOM file holds important acquisition data such as type of equipment used and settings on the modality.
All medical imaging applications that are connected to the hospital network use the DICOM protocol to exchange information, mainly DICOM images but also patient and procedure information.
The DICOM network protocol is used to search for imaging studies in the archive and retrieve images studies to he workstation in order to display.
Pixel data in DICOM images can be compressed using a variety of standards, including JPEG, lossless JPEG, JPEG 2000, ...
DICOM uses three different data element encoding schemes. WIth explicit value representation (VR) data elements, the format for each data elementsis :
GROUP (2B) -- ELEMENT (2B) -- VR (2B) LengthInByte (2B) -- DATA (variable length).