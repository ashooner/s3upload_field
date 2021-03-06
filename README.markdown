Field: Amazon S3 File Upload
-------------------------------------------------------------------------------

Version: 0.5.1 alpha  

Author: Andrew Shooner & Brian Zerangue

Build Date: 2010-06-24

Requirements: Symphony 2.0.6



##Origin

This extension is a variation of the 'Unique File Upload Field' extension by 
Michael Eichelsdoerfer and the Akismet extension (for System Preferences) by 
Alistair Kerney. It uses the Amazon S3 PHP class written by Donovan Schonknecht, http://undesigned.org.za/2007/10/22/amazon-s3-php-class.
This extension was started by Brian Zerangue, and the current working version was written by Andrew Shooner.

##Status
Version .5 of this extension functions as a basic replacement for file uploads, allowing hosting on Amazon S3 (it requires an [Amazon S3 account](http://aws.amazon.com/s3/)). Uploaded files are world readable. It is not considered feature-complete; there is much additional functionality that could be added .If you have input, please contact Andrew Shooner [through email](ashooner@gmail.com) or at the Symphony forums. 


##Installation

1. Upload the 's3upload_field' folder in this archive to your Symphony 
   'extensions' folder.

2. Enable it by selecting the "Field: Amazon S3 Upload", choose Enable from 
   the with-selected menu, then click Apply.

3. Under Preferences, add your S3 Access Key ID and Secret Access Key.

3. You can now add the "Amazon S3 File Upload" field to your sections. Select the bucket you wish to store files in from the dropdown.



##Change Log

___.5.1 alpha - AS___
- Corrected fatal error in field commit() function.

___.5 alpha - A.S.___
- Added S3 class functionality.
- Decided on public-read permissions for simplest usage.
- Put bucket selection in Section editing view.
- Stripped out some extraneous code from upload field this field is based on (Needs more pruning).

___.1.0 alpha - B.Z___
- Initial release - posting code to work off of base. Need to integrate Amazon S3 class now.


