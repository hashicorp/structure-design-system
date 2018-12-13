# Guide Drawer

The Guide Drawer helps a user learn about the product by letting them use the real UI.

## Visual Examples
| Default | Adding Options | Adding Media |
| --- |---| --- |
| ![](https://drive.google.com/uc?id=19uRGfYFWxSn7sRrlVIAXy5MsV7fcucQ1) | ![](https://drive.google.com/uc?id=1tUvdz24bEEJalNCHKez3SyIW6dO5H-kL) | ![](https://drive.google.com/uc?id=1lS44XB8knV1ORL7dkcas8_02VA02M-eJ) |
| Add options to the drawer so that the user can choose where to go next. | A typical guide step includes instructive copy telling the user how to use the normal product interface and can include external links to more information. | Drawer content can include things like images, illustrations or videos. |

## Best Practices

### Guide Drawers should...:

- ✅ Stay fixed to the right of the viewport on desktop, 12px of spacing below the header and on the right and bottom sides
- ✅ Be easily dismissed through the "..." context menu in the upper right
- ✅ Include a section title, a page title, and instructive copy
- ✅ Indicate the progress through the progress bar including milestones
- ⛔️ Not be shown unless triggered by a Guide Trigger

### Drawer section titles should...:

- ✅ Be short (preferably a single word for that feature)
- ✅ Be title-case
- ✅ Match the step titles to help orient the user during multi-step tours

### Drawer content should...:

- ✅ Describe what the user is seeing on the screen
- ✅ Include instructions for what the user should do and why
- ✅ Include links to outside references such as Learn pages, Docs, API docs, videos, etc
- ✅ Rely on docs to provide depth of knowledge rather than distract from the page content
- ✅ Give the user an expectation of time required ("About 10 minutes") next to the Start button when choosing features to tour
- ⛔️ Never use acronyms or product-specific jargon without explaining them

### Drawer progress bars should...:

- ✅ Show a tooltip on hover showing the section title and "Step X of Y". Do not include the step copy elsewhere in the drawer.
- ✅ Always end the last step showing the final milestone as completed and include congratulatory copy
- ⛔️ Never show an empty progress bar. If a user is on step 1 of 3, think of it as 0 of 4 and show the bar 25% filled. This helps the user feel that just getting started is the first step.

## References

- [Component in Abstract](https://share.goabstract.com/d6532206-444d-4752-a396-56fe0641228c)
- [RFC for original Vault UI Guide](https://docs.google.com/document/d/1QZTtQmsYQ4_cZNxrs1A5c1FbJLjvOtDLyz2QRTPuq44/edit#)

## Related Components
- [Guide Trigger](guide-trigger.md)
