## Overview

React Step Wizard is a flexible multistep wizard component built for React. Simply wrap your components in `<StepWizard></StepWizard>` and each child becomes an individual step with automatic navigation controls.

## Features

- Simple wrapper component
- Each child is a step
- Custom transitions
- Hash-enabled navigation
- URL sync with steps
- Programmatic navigation
- Navigation callbacks
- Step validation
- Dynamic steps
- Persistent state
- Custom navigation buttons
- Progress tracking
- Conditional steps
- TypeScript support
- No external dependencies

## Navigation Methods

- nextStep(): Move to next step
- previousStep(): Go back
- goToStep(step): Jump to specific step
- firstStep(): Go to first
- lastStep(): Go to last

## Props Passed to Steps

- currentStep: Current step number
- totalSteps: Total number of steps
- isActive: Boolean for active step
- previousStep: Navigation function
- nextStep: Navigation function
- goToStep: Jump function

## Callbacks

- onStepChange: When step changes
- onBeforeChange: Before step change (validation)

## Use Cases

- Multi-step registration forms
- Checkout processes
- Survey forms
- Onboarding flows
- Configuration wizards
- Application workflows

## Pricing

Free and open-source under the MIT license.