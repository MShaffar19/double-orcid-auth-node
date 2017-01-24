# Case 2: Neither app has existing permission (without Publisher Pals redirect screen)

This demo shows a case where:

- Neither Publisher Pals nor DOI Dudes currently has permission to access the user's ORCID record
- No redirect screen is shown after user grants permission to Publisher Pals - user is sent directly to DOI Dudes authorization screen

###1. Connect iD to Publisher Pals
On the Publisher Pals site, user clicks **Create or Connect your ORCID iD** 

![text fields](readme_images/author_fields.png "Add author name and email address")

###2. Register/sign into ORCID & grant permission to Publisher Pals
 A request to grant Publisher Pals access to the user's ORCID record appears in a pop-up. This page is hosted by ORCID and includes information about the specific actions that Publisher Pals wants to take on the user's ORCID record.

 - **New ORCID users:** Click **Register Now**, complete the registration form and click **Authorize**
 - **Existing ORCID users:** Enter ORCID account credentials and click **Authorize**

![Granting permission to Pub Pals](readme_images/pubpals_permission.png "Grant permission to Pubpals")

###3. Grant permission to DOI Dudes
 A request to grant DOI Dudes access to the user's ORCID record appears in the same window. This page is hosted by ORCID and includes information about the specific actions that DOI Dudes wants to take on the user's ORCID record.

 The user signed into ORCID during step 2, so the sign in form is not displayed. Instead, the user simply clicks **Authorize**.

![Click Authorize](readme_images/doidudes_permission.png "DOI Dudes authorization screen")

###4. DOI Dudes confirmation message

After granting access to DOI Dudes, the user is directed to a screen showing a confirmation message. This page is hosted by DOI Dudes, and DOI Dudes determines its content. This window should be configured to close automatically after several seconds.

![DOI Dudes Thank you](readme_images/doidudes_redirect.png "You have now granted DOI Dudes access to your record")

###5. User returns to Publisher Pals submission system 
The user is returned to Publisher Pals to complete the submission process. Both Publisher Pals and DOI Dudes have permission to access the user's ORCID record. Publisher Pals uses its access immediately to include the user's ORCID iD with the submission; DOI Dudes uses its access to post the work to the user's ORCID record once it is published. 

![Completed submission form](readme_images/pubpals_complete.png "Completed Pub Pals submission form")
