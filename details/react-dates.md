## Overview

React Dates is Airbnb's datepicker library for React, designed to be easily internationalizable, accessible, and mobile-friendly. It powers the date selection on Airbnb.com and has become a popular choice for date picking in React applications.

## Features

- **Internationalization**: Easy to localize for any language
- **Accessibility**: WCAG compliant with keyboard navigation
- **Mobile-Friendly**: Optimized touch interactions
- **Date Ranges**: Select start and end dates
- **Single Dates**: Pick individual dates
- **Customizable**: Extensive styling and behavior options
- **Validation**: Block dates based on custom logic
- **Moment.js**: Built on Moment.js for date handling

## Main Components

### DateRangePicker
Select a range of dates with start and end dates. Fully controlled component with callbacks for date changes.

### SingleDatePicker
Pick a single date with calendar popup. Supports all standard datepicker features.

### DayPickerRangeController
Low-level component for building custom date range interfaces.

## Key Features

- Minimum and maximum date restrictions
- Blocked and highlighted dates
- Custom day rendering
- Month navigation
- Year selection
- First day of week customization
- Number of months displayed
- Orientation (horizontal/vertical)

## Customization

- Custom CSS styling (Aphrodite-based)
- Custom phrases for i18n
- Custom day size
- Custom icons
- Input styling
- Calendar styling
- Custom render functions

## Validation & Blocking

- Block dates in the past
- Block dates in the future
- Block specific dates
- Block date ranges
- Custom blocking logic
- Highlighted dates

## State Management

Fully controlled components requiring:
- startDate/date props
- endDate prop (for ranges)
- onDatesChange/onDateChange callbacks
- focusedInput prop
- onFocusChange callback

## Browser Support

Supports all modern browsers including mobile Safari, Chrome, Firefox, and Edge.

## Use Cases

- Hotel booking systems
- Travel reservation interfaces
- Event scheduling
- Vacation rental platforms
- Appointment booking
- Date range filtering
- Calendar applications

## Community

Widely adopted with ~350k weekly npm downloads and active community support.

## Pricing

Free and open-source under the MIT license.