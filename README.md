# AD-Photo-import
This is a script that imports photos into Active Directory using the thumbnailPhoto attribute of the user.
In this script, it is pulling from a populated directory of photos that our IDM system provides. The photo file for each user is name employeeID.jpg (123456.jpg)

The resize function resizes the photo to the correct size and aspect ratio for AD and sets it to the attribute. The Mmsspp sync process will pick this attribute up for O365, outlook and skype/lync photos from there.
