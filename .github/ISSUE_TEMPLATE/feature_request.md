---
name: Feature request
about: Log a feature or enhancement request
title: Short description of feature in Sentence case, no full stop
labels: enhancement
assignees: ''

---

## Summary

1. **As a** [user concerned by the story]
1. **I want** [goal of the story]
1. **so that** [reason for the story]


## Acceptance Criteria

1. [If I do A, B should happen]
1. [If I do C, D should happen]


## Wireframes and mockups

### [Title of wireframe/mockup 1]
[Image of wireframe/mockup 1]

### [Title of wireframe/mockup 2]
[Image of wireframe/mockup 2]

## Notes

* > Here goes a quote from an email
* Here goes any other useful information…

## Developer Testing
_Requestor:_ leave this section blank
_Developer:_ complete this section during commit/pull request 

**Positive testing:**

Add all the things that you have checked whilst completing this story here, it should be written in a non-technical way, and a lot of this can probably be taken from the acceptance criteria, here are two different examples:  
- **I checked that** the language of the page changed to Spanish **when** I selected Spanish in the language dropdown  
- **I checked that** the list filtered correctly **when** I added an isBefore date filter on list block  

**Negative testing:** 

Here you list the things you have checked where your code needs to show an error, handle unusual/bad input/config gracefully, or may impact separate features that use or depend on the same code. Pause and think -- they may not be obvious!  Examples:    
- **I checked that** there was no "Select language" dropdown option **when** there is only one language configured
- **I checked that** a nice error is shown **when** a language is selected, but the page isn't translated into that language yet
- **I checked that** my list filter code changes didn't cause problems **when** filters are used in other places like ACLs, workflow if/then, and select list filters
- **I checked that** in list filters, I can only select a date type property for the "Value" field, **when** the "Property" field is a date type property

**e2e test links and description:**
- http://www.Link-to-Ghost-inspector-test.com - and paste the test description here
- http://www.Link-to-another-Ghost-inspector-test.com - and paste the test description here
