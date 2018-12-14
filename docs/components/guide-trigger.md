# Guide Trigger

The Guide Trigger provides information related to the Guide Drawer. This is usually an invitation which will open the drawer, but can also provide supplemental information such as thanking the user for taking the tour.

## Visual Examples
| Intro | Later | Default |
| --- |---| --- |
| ![](https://drive.google.com/uc?id=1PCWsD3H5hsQV0-Bls2cRPOjbnepwPiVj) | ![](https://drive.google.com/uc?id=1-VgqaIchhPVIVx8R3ZYXU6QwI5_h4JUa) | ![](https://drive.google.com/uc?id=11uAZFoUNTjysXLM5fD32B38dM_atfxcG) |
| The intro trigger invites the user to take a tour but does not force them to. | The later trigger provides a subtle invitation to learn about a specific feature. | The default trigger is customizeable and will work for any other case. |

## Best Practices

### Guide Triggers:
- Triggers should stay fixed to the upper-right of the viewport on desktop, and fixed to the bottom of the viewport on mobile
- Position the trigger 12px below the header and 12px from the edge of the viewport, just like the drawer
- Include a horizontal line on the intro trigger that should match the product brand color, but brand colors appear nowhere else
- The trigger should be the same width as the drawer that will open
- The trigger should never take more than a single click to dismiss
  - If the user closes a trigger, it should not appear again when they revisit the page
  - If you need to remind the user of the guide, use the more subtle later trigger with simple "Learn about X" copy
  - If the user closes a feature-specific trigger, it should not show up again anywhere in the feature

### Trigger titles:
- Keep the title short (preferably a single word)
- The title should never be more than one line
- Use title-case
- Inform the user what they will be touring


### Trigger content:
- Should be supportive of and related to the title
- Keep the content short (preferably 3 lines or shorter)
- There should not be any content in the "later" trigger style

## References

- [Component in Abstract](https://share.goabstract.com/d6532206-444d-4752-a396-56fe0641228c)
- [RFC for original Vault UI Guide](https://docs.google.com/document/d/1QZTtQmsYQ4_cZNxrs1A5c1FbJLjvOtDLyz2QRTPuq44/edit#)

## Related Components

- [Guide Drawer](guide-drawer.md)
