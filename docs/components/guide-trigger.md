# Guide Trigger

The Guide Trigger provides information related to the Guide Drawer. This is usually an invitation which will open the drawer, but can also provide supplemental information such as thanking the user for taking the tour.

## Visual Examples
| Intro | Later | Default |
| --- |---| --- |
| ![](https://drive.google.com/uc?id=1PCWsD3H5hsQV0-Bls2cRPOjbnepwPiVj) | ![](https://drive.google.com/uc?id=1-VgqaIchhPVIVx8R3ZYXU6QwI5_h4JUa) | ![](https://drive.google.com/uc?id=11uAZFoUNTjysXLM5fD32B38dM_atfxcG) |
| The intro trigger invites the user to take a tour but does not force them to. | The later trigger provides a subtle invitation to learn about a specific feature. | The default trigger is customizeable and will work for any other case. |

## Best Practices

### Guide Triggers should...:

- ✅ Stay fixed to the lower-right of the viewport on desktop, and fixed to the bottom of the viewport on mobile
- ✅ Be 12px below the header and 12px from the edge of the viewport, just like the drawer
- ✅ Include a horizontal line on the intro trigger that should match the product brand color, but brand colors appear nowhere else
- ✅ Be the same width as the drawer that will open
- ⛔️ Never take more than a single click to dismiss
  - If the user closes a trigger, it should not appear again when they revisit the page
  - If you need to remind the user of the guide, use the more subtle later trigger with simple "Learn about X" copy
  - If the user closes a feature-specific trigger, it should not show up again anywhere in the feature

### Trigger titles should...:

- ✅ Be short (preferably a single word)
- ✅ Be title-case
- ✅ Inform the user what they will be touring
- ⛔️ Never be more than one line


### Trigger content should be...:

- ✅ Supportive of and related to the title
- ✅ Short (and preferably 3 lines or shorter)
- ⛔️ Not included in the later trigger style

## References

- [Component in Abstract](https://share.goabstract.com/d6532206-444d-4752-a396-56fe0641228c)
- [RFC for original Vault UI Guide](https://docs.google.com/document/d/1QZTtQmsYQ4_cZNxrs1A5c1FbJLjvOtDLyz2QRTPuq44/edit#)

## Related Components

- [Guide Drawer](guide-drawer.md)
