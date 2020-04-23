# Suggested improvements

## Add the ability to filter elements
I would add this feature to simplify the filtering of the emails. I can implement this function extending the capabilities of the current sortResults function and adding the relevant filtering input fields at the top of the page. It would allow to filter, for example, items that have an attachment or items that have certain keywords in certain fields.

## Ability to "save" emails
I would allow the user to "save" an email, and give the ability to view and filter only within the saved emails. This would be easily doable by adding a separate array of "saved" items.

## Add a pager
Adding a pager can help the user to view large numbers of emails without causing loading issues. I would use one of the available react components (for example the rsuite Pagination component https://rsuitejs.com/en/components/pagination) or code a pagination compoment myself.

## Add a loader
I would add a loader to be shown when fetching data; it would be beneficial when fetching it from remote resources. I would use one of the existing components or code on myself, toggling the visibility of the content until it's been fully retrieved.

## Add a different view
I would allow the user to click on an icon to display the emails list with a different layout: basically instead of "flex-direction: row" I would use "flex-direction: column" to show all the text contained in the fields without ellipsis. Otherwise it would be possible to add resizable columns or an icon that when clicked expands the selected column to view its content.

## View hidden recipients
Currently it's possible to view the hidden recipients by hovering the mouse on the "To" field of the list. I would add the ability to expand recipients when clicking on the badge. I would implement this by toggling classes on click and removing the "text-overflow: ellipsis" and "white-space: nowrap".

## Open email
Adding the ability to open the email and view its content (currently available only on mobile when tapping on the date field with the arrow icon).