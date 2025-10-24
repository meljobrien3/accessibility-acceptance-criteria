
 

## AAC1 Keyboard access
Given I am a keyboard user when I encounter interactive content then I can control it solely from the keyboard.
App: External keyboard (e.g. Bluetooth keyboard)
Web: Laptop or desktop keyboard

## AAC2 Zoom & Resize
App: Given I increase to largest text size in the system settings, 
Web: Given I use browser zoom of 400%, 

I can still read everything and nothing is cut off. Text should not be truncated “…” unless the same information is available nearby.

## AAC3 Focus Management
Given I am a keyboard or screen reader user, when I navigate through the page, focus should move in a logical order (left to right, top to bottom).
And
When I go to a new page and come back or update an element on the screen (e.g. product or list quantity)

Then return the focus to where I was on the screen, or the next logical item.

## AAC4 Semantic markup used appropriately
Given I use a screen reader, when I encounter content which looks visually different, then it’s been coded properly (semantically) so I can understand what it is. E.g. headings, ordered and unordered lists, tables, bold text and more).

## AAC5 Form fields 
Given I use a screen reader, when I interact with a form field, it has a visible label (avoid placeholder text), and the label, hint text or error message is read out when I’m on the form field.  

## AAC6 Error handling 
Given I use a screen reader when I input an error in a form field and then press the main continue call to action button, I'm notified audibly and can understand what's required to correct the error, and focus moves to the first field in error.

## AAC7 Orientation
Given I use a mobile device, when I change the screen orientation from portrait to landscape, the content reflows, and I can still see the same content. 

## AAC8 Status updates
Given I use a screen reader, when a visual change occurs on the page, then I can hear that change  announced (politely) so I don’t miss it, and my focus stays in the same place.

## AAC9 Alt text
Given I use a screen reader, when I encounter an informative (important) image it should read out appropriate alt text. If the image is decorative, it should be hidden from the screen reader.  
Examples include: search results displaying, progress bar value changes (minimum order value), errors after activating submit button.

## AAC10 Screen reader only text
Given I use a screen reader, when I read content, then it makes sense even out of context and has additional screen reader only text included when necessary.  
Note: On-screen text must always be the first part of the accessibility text for interactive elements (button, links). 

