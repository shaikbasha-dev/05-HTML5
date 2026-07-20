# Date and Time Inputs

## Introduction

HTML5 introduced several input types for selecting dates and times. These input controls provide built-in calendars and time pickers, making it easier for users to enter accurate date and time information without manually typing values.

Using these input types improves user experience, minimizes input errors, and provides consistent formatting across modern web browsers.

---

# Date Input

The `date` input allows users to select a calendar date.

## Syntax

```html
<input type="date">
```

---

## Example

```html
<label for="dob">Date of Birth</label>

<input
    type="date"
    id="dob"
    name="dob"
>
```

---

# Time Input

The `time` input allows users to select a specific time.

## Syntax

```html
<input type="time">
```

---

## Example

```html
<label for="meetingTime">Meeting Time</label>

<input
    type="time"
    id="meetingTime"
    name="meetingTime"
>
```

---

# Datetime-Local Input

The `datetime-local` input allows users to select both a date and a time without a time zone.

## Syntax

```html
<input type="datetime-local">
```

---

## Example

```html
<label for="appointment">Appointment</label>

<input
    type="datetime-local"
    id="appointment"
    name="appointment"
>
```

---

# Month Input

The `month` input allows users to select a month and year.

## Syntax

```html
<input type="month">
```

---

## Example

```html
<label for="joiningMonth">Joining Month</label>

<input
    type="month"
    id="joiningMonth"
    name="joiningMonth"
>
```

---

# Week Input

The `week` input allows users to select a specific week of a year.

## Syntax

```html
<input type="week">
```

---

## Example

```html
<label for="projectWeek">Project Week</label>

<input
    type="week"
    id="projectWeek"
    name="projectWeek"
>
```

---

# Common Attributes

## min

Specifies the earliest selectable date or time.

Example:

```html
<input
    type="date"
    min="2026-01-01"
>
```

---

## max

Specifies the latest selectable date or time.

Example:

```html
<input
    type="date"
    max="2026-12-31"
>
```

---

## value

Specifies the default selected value.

Example:

```html
<input
    type="date"
    value="2026-07-20"
>
```

---

## required

Makes the field mandatory.

Example:

```html
<input
    type="date"
    required
>
```

---

# Complete Example

```html
<form>

    <label for="dob">Date of Birth</label>

    <input
        type="date"
        id="dob"
        name="dob"
        required
    >

    <br><br>

    <label for="meeting">Meeting Time</label>

    <input
        type="time"
        id="meeting"
        name="meeting"
    >

    <br><br>

    <label for="appointment">Appointment</label>

    <input
        type="datetime-local"
        id="appointment"
        name="appointment"
    >

    <br><br>

    <label for="joining">Joining Month</label>

    <input
        type="month"
        id="joining"
        name="joining"
    >

    <br><br>

    <label for="week">Project Week</label>

    <input
        type="week"
        id="week"
        name="week"
    >

    <br><br>

    <input
        type="submit"
        value="Submit"
    >

</form>
```

---

# Advantages

- Built-in calendar and time picker
- Reduces manual input errors
- Consistent date and time formatting
- Improves user experience
- Mobile-friendly controls
- Supports HTML5 validation
- Easy to integrate into forms

---

# Best Practices

- Use the appropriate input type for the required data.
- Specify `min` and `max` values whenever applicable.
- Mark mandatory fields using the `required` attribute.
- Provide meaningful labels for accessibility.
- Validate date and time values on the server side.
- Consider browser compatibility for older browsers.

---

# Real-World Applications

- Date of Birth
- Appointment Booking
- Meeting Scheduling
- Hotel Reservation
- Flight Booking
- Event Registration
- Project Planning
- Attendance Systems
- Interview Scheduling
- Online Examination Timing

---

# Summary

HTML5 date and time input types provide user-friendly controls for selecting dates, times, months, weeks, and combined date-time values. They simplify data entry, improve accuracy, and offer built-in validation, making them essential components of modern web forms.
