# Progress

Progress elements provide feedback for determinate-length tasks.

## Visual Examples

### Default

Three different formats are available to suit space constraints and desired aesthetic.

| Bar | Column | Ring | 
| :---: | :---: | :---: |
| ![](https://drive.google.com/uc?id=1pxy538EdnryJNY_nXPUQIu5ovEObBN6V) | ![](https://drive.google.com/uc?id=1SFwRX_QwrCRB4vaRS8DLmGVZLrzs2izz) | ![](https://drive.google.com/uc?id=1o_iJMIN6QZWrhlozNdFHNCKp3lHN500H) | 


### With additional feedback

It's often helpful to also present the value of the progress element nearby. Below are a few ways of doing so. Ultimately, however, context and constraints will inform the most appropriate implementation.

| Bar with text | Column with text | Ring with tooltip | 
| --- | --- | --- |
| ![Bar with text](https://drive.google.com/uc?id=1VWaMGVwRe6eT8M3_AQSpSV6q3-eLwFI4) |  ![Column with text](https://drive.google.com/uc?id=1hJG88hJdbX4U3w5knBeflKyqLprQ-GTd) |     ![Ring with tooltip](https://drive.google.com/uc?id=1DuaD3DEtee1h2dSnZWXgn8Pvw588iYyF) |

## Best Practices

- Use one of these elements when it's meaningful to communicate progress toward completion. 
- Use when the progress toward completion is known (or can be reliably estimated).
- The blank version of the progress meters can be confusing. Consider showing Step 1 of a process as having already partial completion (e.g. Step 1/3 might already show 33% finished).
- Rather than showing a completed bar, consider replacing it with the action to take next.
- Include a tooltip or helper text near the progress meter to help give details and explain what the progress meter is measuring.

## Resources

- [Component in Abstract](https://share.goabstract.com/9f3f9a13-15e4-4e9d-8718-2d6713ee3658)

## Related Components

- Loaders
- [Guide Drawer](guide-drawer.md)