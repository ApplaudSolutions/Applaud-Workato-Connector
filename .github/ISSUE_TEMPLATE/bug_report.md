---
name: Bug report
about: Log a bug where expected behavior is not working correctly
title: Brief description of issue (not solution) in Sentence case, no full stop, no
  vagueness!
labels: bug
assignees: ''

---

**Describe the bug**
A clear and concise description of what the bug is.

**Steps to reproduce**
1. Navigate to [system] and login as [user]
1. Go to '...'
1. Select '....'
1. Scroll down to '....'
1. See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**URL**
Enter URL

**Additional context**
Add any other context about the problem here.

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
