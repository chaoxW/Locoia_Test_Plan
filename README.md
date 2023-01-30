# Locoia_Test_Plan

# 1. Positive Test cases  
- Check Edit button (**Priority Highest**, from user's perspective it is critical the button should exist, it is the positive coverage)
  1. Click the edit button --> the edit modal window should appear 
  
- Check Delete user button (**Priority Highest**, from user's perspective it is critical the button should exist, it is the positive coverage)
  1. Click the delete button --> the delete modal window should appear

- Check Refresh temporary password button (**Priority Highest**, from user's perspective it is critical the button should exist, it is the positive coverage)
  1. Click the Refresh temporary password button --> the Refresh temporary password modal window should appear
  
- Validate Edit modal window (**Priority Highest**, from user's perspective it is critical to edit the data from the modal window, it is the positive coverage)
  1. Click the edit button --> the edit modal window should appear 
  2. Insert the corret data type in the modal window --> data corretly inserted
  3. Click the save button --> the data saved correctly with correct notification message
  
- Validate Delete user button (**Priority Highest**, from user's perspective it is critical the button should delete the user, it is the positive coverage)
  1. Click the delete button --> the delete modal window should appear
  2. Click Yes button --> the user has been deleted correctly with correct notification message
  
- Validate Refresh temporary password button (**Priority Highest**, from user's perspective it is critical to udpated the temporary password, it is the positive coverage)
  1. Click the Refresh temporary password button --> the Refresh temporary password modal window should appear
  2. Update the temporary password with correct length and data type required --> the correct data inserted
  3. Click update button --> the password correctly updated with correct notification message
  
# 2. Negative Test cases  
- Missing madatory data from edit modal window (**Priority Highest**, from user's perspective it is critical to edit the data from the modal window, it is the negative coverage)
  1. Click the edit button --> the edit modal window should appear 
  2. Do not insert the madatory data (first name, last name, Email, Mobile, Title) and click the save button --> correct error message shown with correct information about missing the mandatory data

- Insert madatory data from edit modal window with wrong data type(**Priority Highest**, from user's perspective it is critical to edit the data from the modal window, it is the negative coverage)
  1. Click the edit button --> the edit modal window should appear 
  2. Insert the first name with numbers and special characters --> correct error message shown with correct inforamtion about the wrong data type
  3. Insert the last name with numbers and special characters --> correct error message shown with correct inforamtion about the wrong data type
  4. Insert the email with wrong foramt (missing @) --> correct error message shown with correct inforamtion about the error email format
  5. Insert the title with numbers and special  characters--> correct error message shown with correct inforamtion about the wrong data type
  
- Cancel Delete user (**Priority Highest**, from user's perspective it is critical the button should not delete the user, it is the negative coverage)
  1. Click the delete button --> the delete modal window should appear
  2. Click Cancel button --> the user not delete, not shown the notification message
  
- Cancel Refresh temporary password button (**Priority Highest**, from user's perspective it is critical to cancel udpated the temporary password, it is the negative coverage)
  1. Click the Refresh temporary password button --> the Refresh temporary password modal window should appear
  2. Update the temporary password with correct length and data type required --> the correct data inserted
  3. Click cancel update button --> the password correctly did not update, not shown the notification message
