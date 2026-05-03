# Registration Page - MVP Plan

## *1. Model Layer**
- `User.ts` - Data class for registration info
- `RegistrationRepository.ts` - Handles API calls or DB storage

## *2. Presenter Layer**
- `RegistrationPagePresenter.ts`
- Implements validation logic
- Interacts with Repository to save data
- Updates the View with errors or success

## *3. View Layer**
- `RegistrationPageView.ts`
- Interface implemented by Activity/Fragment
- Shows/hides errors
- Sends user actions to Presenter

## *4. UI Layout**
- `RegistrationPageLayout.xml`
- Editable fields for Full Name, Email, Password, Confirm Password, Phone
- Submit Button
- Error display components

## *5. Testing**
- Unit tests for Presenter logic
- UI tests for form submission and validation workflow
