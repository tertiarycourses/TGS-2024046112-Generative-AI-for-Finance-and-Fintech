# Agent flow notes

Verified on a live tenant. Believe these over what the designer appears to do.

## Inserting values
- Always insert dynamic values with the picker. The Instructions editor escapes underscores in
  node names, and a reference to a missing node resolves to empty rather than erroring: the node
  stays green and the agent silently receives nothing.

## SharePoint
- Pick the site from the dropdown, never a typed URL.
- Normalise the key inside the filter query, not after it.
- `Get items` with a filter query returns list rows; agent knowledge does not.

## Human review
- The Human review node always fires. The agent 'request help' toggle only fires when the model
  feels unsure, so it is not a control.
- The Yes/No input publishes the string `Yes`, not boolean true. Compare against `Yes`.
- Leave the outcome default blank so inaction fails safe.
- Use the Teams channel. Outlook created the request but never delivered it.
- Address `assignedTo` by typing the full address, waiting for the lookup and clicking the suggestion.

## Diagnosing
- A green run does not mean the work happened. A node in 'Needs setup' is skipped silently.
- Moving a node clears its configuration. Reopen and refill every field.
- Read the UPSTREAM node's Run Details Outputs before your second fix attempt.
- Two identical failures mean the theory is wrong, not the fix.
- Confirm Published, not Draft, before believing any test result.
