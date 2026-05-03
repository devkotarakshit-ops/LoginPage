# Registration Page - MVVM Plan

## *1. Model Layer**
- `User.ts` - Data class for registration info
- `RegistrationRepository.ts` - Handles API calls or DB storage

## *2. ViewModel Layer**
- `RegistrationViewModel.ts`
- Exposes LiveData/StateFlow for input validation and submission status
- Handles validation rules
- Calls Repository to save data

## *3. View Layer**
- `RegistrationView.ts`
- Observes ViewModel for validation errors and submission results
- Displays UI components from 'registration-component.xml'
- Handles user input and sends data to ViewModel

## *4. UI Layout**
- `RegistrationPageLayout.xml`
- Editable fields for Full Name, Email, Password, Confirm Password, Phone
- Submit Button
- Error TextViews

## *5. Testing**
- Unit tests for ViewModel validation logic
- UI tests for form submission and validation workflow
