# Pagination

Pagination enables users to navigate a set of records that are distributed across multiple pages. It is comprised of the following: 

| Element | Description | Required? | 
| --- | --- | --- | 
| Page Buttons | Allows direct navigation to specific pages within a set | Yes | 
| Previous / Next Buttons | Allows user to move forward or backwards in the set, depending on the current page | Yes |
| Ellipses | Indicates a truncated range of pages | No | 
| Summary Label | Indicates the range of results shown on the current page | Yes | 
| Page Controls | Allows user to increase / decrease the number of records displayed per page | No | 

## Visual Examples

### Basic

The basic state does not contain Page Controls. 

![Basic Pagination](https://drive.google.com/uc?id=1VFRLGqWlcxBb19Fb7ZCoIFIS6ijj3beo)

### With Table Footer

Pagination can be enclosed within a table footer. 

![Pagination inside a table footer](https://drive.google.com/uc?id=1wq5Hk9jNUNYYI5fsIteoaCaVdM7Xf7wl)

### With Page Controls

The designer may elect to allow users to change the number of results per page. 

![Pagination with Page Controls](https://drive.google.com/uc?id=1IJr95MN_ga6OVFJKQjz8MgTJ911R8_56)



## Best Practices

### Usage

- Place Pagination immediately following the set of records it controls
- Center align the Pagination
- Left align the Summary Label and, if used, Page Controls
- Optionally enclose the Pagination in a Table Footer
- Don't display Pagination if there is only one page of results

### Page Buttons

- Show at most 7 Page Buttons
- Always show the first and last page 
- Use the Primary button style to identify the current page

### Previous / Next Buttons

- Always show Previous and Next buttons
- Disable the Previous button if the user is on the first page in the set
- Disable the Next button if the user is on the last page in the set

### Ellipses

- Use ellipses (&hellip;) if the number of pages is greater than 6
- When shown, ellipses appear immediately after the first page and/or immediately before the last page
- The Page Buttons between ellipses may change depending on where the user is in the set. For example:
  - [1] **[2]** [3] [4] [5] [6] ... [50]
  - [1] ... [28] [29] **[30]** [31] [32] ... [50]
  - [1] ... [45] [46] **[47]** [48] [49] [50]

## Summary Label

- Show the range of results currently displayed, _not_ the page number

## Page Controls

- When permitted, the user may change the number of results displayed per page
- These increments are predetermined; users cannot choose an arbitrary value

## References

- [Component in Abstract](https://share.goabstract.com/072b45e8-05b8-48f2-bcb9-36c56e9efd7f)
