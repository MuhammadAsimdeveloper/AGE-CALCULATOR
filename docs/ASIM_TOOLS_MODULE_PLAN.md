# Asim Tools Module Plan — AGE-CALCULATOR

Date: 2026-10-08

## Role
age-calculation project

## Runtime rule
Use copied local modules only. Do not call Asim Tools at runtime, do not iframe/link to its tool pages for execution, and do not add a standalone "Tools" section to this product.

## Assigned starting modules
- `age-calculator`
- `date-difference`
- `percentage`
- `average`
- `median`
- `project-health-scanner`
- `env-redactor`
- `secret-scanner`

## Notes
Keep the project focused on its calculator product. Do not add an Asim Tools catalog or separate tools navigation.

## Implementation gate
1. Establish the repository's product purpose.
2. Copy only the required module implementation and focused tests.
3. Add the module to the existing backend/service layer.
4. Keep the implementation self-contained and free of remote Asim Tools dependencies.
5. Do not copy UI code; backend modules are the integration contract.
