## Outlook Export Not Available for MacOS
- **Issue:** On file menu, Export button is missing in Outlook.
- **Root Cause:** Outlook classic service closed on Mac.
- **Solution:** Switched to legacy mode -> login -> file menu to export as OLM file

## Mac did not have enough capacity to have backup file 
- **Issue:** User's Mac had insufficient capacity to save files.
- **Root Cause:** Due to 700Gb documents, lack of disk capacity occurred. 
- **Solution:** On default mail program, deleted account which also deletes mails. Also recommended to use portable SSD to upload backup files. 

## Data file didn't save properly with loss of files
- **Issue:** Users having issue with backup data loss on PST/OLM
- **Root Cause:** Network connection was unavailable and size of backup was large
- **Solution:** Provided SSD, created step-by-step guide to separated mails into several folders. Notified user to load and validated backup files. 

## POP login on outlook was not available 
- **Issue:** When switching to Outlook classcic, encrypted password enter was required
- **Root Cause**: User's mail Outlook profile conflicted therefore it pushes out user from login
- **Solution:**: Recreated profile on control panel for this user without connecting anything, set it as default then logged in with POP account. 

## Backup file installed all data including non-POP account
- **Issue:** User created backup file but it installed all of mails user logged in on Outlook
- **Root Cause:** Mac Outlook does not support to create OLM file on specific folder.
- **Solution:**: Guided user to log out on accounts that does not require to have back up mails. 

## Shared mail from previous service isn't available
- **Issue:** A mail that's shared with other users are unavailable
- **Root Cause:** Account was on previous mail service. After changed to Exchange, old account is closed.
- **Solution:** Created groupmail account and added all of users who used to share that account to receive emails. Set delegate to send as groupmail address

## Setting sender as groupmail address failed
- **Issue:** Sending mail as groupmail address was not found on Outlook web.
- **Root Cause:** On Web version, it's hidden unless change it on settings.
- **Solution:** Go to Settings -> Compose and Reply -> check Always show From it displays to change their mail sender as groupmail. 

## Lost password on second login 
- **Issue:** User lost password after login on second time.
- **Root Cause:** After user's first login, user changed password but lost it
- **Solution:** On admin center, reset user's password and gave temporary password, required to change password to be secured. 

## Shipfix program blocked user and required admin authorization
- **Issue:** User could not login with Shipfix
- **Root Cause:** Shipfix login required admin authorization when login with 365 Account
- **Solution:** With administrator account, assigned Shipfix permission to account

## Outlook mails cannot receive or send mails
- **Issue:** User could not send or receive any mails from Outlook
- **Root Cause:** Users who had same issue did not logout their POP account. It has same domain name as before. 
- **Solution:** Logged out of old account and logged in with Exchange account with same domain name resolved issue.