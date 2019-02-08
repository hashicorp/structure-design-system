# Button

Used to initiate an action, whether submit a form to kick off a workflow.

## Visual Examples

| Primary                                                                             | Secondary                                                                             | Warning                                                                             | Ghost                                                                             | Link                                                                             |
|-------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| ![Primary button](https://drive.google.com/uc?id=1-3gtN-rg9BoUFC2So99n8zIeedSUgJV8) | ![Secondary button](https://drive.google.com/uc?id=1B-TRBrXmTascB_0kCwUphMo4sLxUyX5i) | ![Warning button](https://drive.google.com/uc?id=1WePWSVVMOkfOZ9NZOYp4dgLwYZOxa9Tp) | ![Ghost button](https://drive.google.com/uc?id=1VHf2ndt84vBwNz0f7AzejVf1MuN6PlqT) | ![Inline Link](https://drive.google.com/uc?id=1-AvSo1qlOuoJUmB6fMiO_VPECWzXHaW_) |

## Best Practices

- Text buttons should be ≥ 100px wide. Icon-only buttons should be 36px wide.
- Labels should be concise and sentence case.
- Labels should be action-oriented and describe the action to be performed. Avoid using the label "Submit".
- There should only be one primary button within a page, modal, or popover.
- All products should use the primary button style, but may override the primary button color with their product color.
- When used side by side, the buttons should maintain a margin of 12px between each other.
- Use the danger button for irreversible actions where the user stands to lose a lot of work. When used, consider introducing additional friction (e.g. confirmation modal) to prevent accidental actions.
- When a button is disabled, it’s useful to provide an additional affordance (e.g. tooltip  or cursor:not-allowed) to communicate why.
- Icon-only buttons should provide a non-visual affordance—such as visually hidden text or use of the aria-label attribute—for improved accessibility. 
- Ghost buttons are most commonly used when multiple buttons are adjacent to one another (e.g. context menus), where additional borders would create undue noise. They may also be used as for tertiary actions.
- If an action will take between 2 and 10 seconds to complete, consider embedding a loader to communicate to the user that work is being done. If it takes longer, additional feedback mechanisms may be needed to set expectations for the user.
- In areas with minimal space, such as tables, any button can be made to compact vertically to 28px height. Left and right padding and minimum width should remain the same. Primary buttons should avoid using compact styles.


## References

- [Component in Abstract](https://share.goabstract.com/0de536fe-fe1a-46d0-a04c-f1790941a920)

## Related Components
- Dropdown
- Loader
- [Pagination](./pagination.md)
