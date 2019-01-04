# Structure Design System

Structure is a Design System for HashiCorp Web UI projects.

## Getting Started

#### Read the Documentation

- [Status](docs/status.md)
- [Components](docs/components)

#### Design

Our Design System is designed in Sketch and [stored in Abstract](https://share.goabstract.com/0b159f72-b8fb-4441-9ccc-65a1a4ec995d) for sharing and organizing. If you don’t have access to Abstract, ask in [#proj-product-ds](https://hashicorp.slack.com/messages/C7KTUHNUS/).

## Contributing

#### What should go in Structure?

The most obvious candidate are those design patterns (or similar variants) used in multiple products. If you have a component you think we should be using or think that we could be doing something better, these are also good bets. Not sure? Ask in [#proj-product-ds](https://hashicorp.slack.com/messages/C7KTUHNUS/)

#### What should an entry contain?

The content of each entry is flexible and evolving. Generally speaking, however, an entry should contain:

| Section | Description | 
| --- | --- |
| Overview | 1-2 line description of the component and it's purpose. |
| Visual Examples | Screenshots of the component and any important states. Store these in [Google Drive](https://drive.google.com/drive/folders/11vuTznb1M-_SFxSILxqjdkF_R8g7p9ya). | 
| Best Practices | Instructions for usage. Include functional requirements if they are significant and not apparent. Omit design characteristics like spacing, color, and fonts, that can be derived from Abstract. | 
| References | Link to any additional materials that are helpful. At a minimum, link to the Abstract artboard (master branch). |
| Related Components | Link to any other components that share similar functionality, have similar aesthetics, or solve similar problems. | 

#### What's the process for contributing? 

- Assign yourself a Task on the [Structure Asana Board](https://app.asana.com/0/932595914516336/board).
- Create a new branch off of `master`. 
- Make your edits or additions. 
- Add images to [Google Drive](https://drive.google.com/drive/folders/11vuTznb1M-_SFxSILxqjdkF_R8g7p9ya) if needed. 
  - Export the image in 2x pixel density.
  - Use the naming convention `component_<component-name>_<name-of-state>`.
  - Make sure Link Sharing is enabled and that anyone with the link can access it.
  - Link directly to the image using the URL `https://drive.google.com/uc?id=<YOUR_IMAGE_ID>`.
- Update [Status.md](docs/status.md) if needed.
- Update the Table of Contents in the [Readme](docs/components/README.md) if needed.
- Submit your changes as a Pull Request and request a review. 
- Update the progress of the Asana Task.

## Questions or Feedback

Please discuss in the [#proj-product-ds](https://hashicorp.slack.com/messages/C7KTUHNUS/) channel in Slack
