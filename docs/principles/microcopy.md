# Microcopy

## Overview

As a writing principle, inclusivity means accounting for the needs of the entire spectrum of users in your writing. These users include persons with physical impairments, persons with dyslexia, persons who are new to your product, and non-native speakers of the language your product uses in its UI and documentation. This guide is a short list of tips. References for a deeper dive can be found below the guide.

**How to use this guide**

Read the four numbered sections below. These will familiarize you with inclusive writing principles. Use the checklists at the end of the document for writing and reviewing your work.

## 1: Write for screen readers

Users with low or no vision often use screen readers to access text on the screen. Screen readers read web pages in a linear fashion. They allow users to read sub-headers and links as lists, saving visually impaired users from having to listen to an entire page in order to locate a single item on it. Make navigating a page easier for a screen reader user by following these guidelines:

- Write headers and sub-headers that describe the content clearly, in a manner that does not require context in order to understand it.
- Avoid using generic linking language, like “More” or “Click here”. Use language that describes the linked content.

- Write alt-tag text for images that describe the image.
- Use periods in directions. Screen readers need a visually indicated pause, in order to read text more naturally.
  Write a descriptive text label for icons.

## 2: Use plain language

Plain language helps users with cognitive disabilities. These include attention deficit disorder, dyslexia and stress-related issues with focus. Plain language is also useful for non-native speakers of your tongue, for whom complex constructions and slang can be time-consuming to understand. To ensure that you are using plain language, follow these guidelines:

- Use the active voice in directions.
- Use short, simple sentences.
- Break large paragraphs into shorter ones, and use bulleted lists instead of comma separated lists.
- Avoid italics, which can be difficult to process for persons with dyslexia.
- Avoid slang.
- Use jargon only when it is clear that your users understand it well (like acronyms within a company or product).

If you’re writing how-to documentation, err on the side of too much and too simplistic an explanation in your first draft. This helps you identify any areas that need disambiguation when you receive a technical review.

Persons with dyslexia (who are believed to be ~10% of the population) can have difficulty reading when blocks are overlong, text is italicized or when justified text creates uneven spacing between letters. For persons with dyslexia, letters can appear to swap places or move slightly. Keep your sentences short. Break the text into small blocks. Avoid italics (which may appear to waver more than regular text). These tactics can help reduce the size of the field of characters the reader with dyslexia has to navigate.

## 3: Account for translation

If your UI's roadmap includes translating it into other languages, start preparing now.

- Use plain language to keep your strings short and easier to translate.
- Determine what terms used in the UI should not be translated: terms specific to your product are probably going to be easier to understand if left untranslated.
- Technical products are a challenge for most third-party translation services. Find out from your PM exactly which language is targeted for the first translation. Then, find a user of your product who natively speaks the target language, and who is willing to act as a consultant. One user will not be able to answer all your questions, but at the very least, they can help you work with a paid translation service.
- If you’re writing UI copy - headers, button labels, column headers - test your copy length against the UI by calculating your longest expected English string length, then adding 50% more characters to test for length to address German translation needs. Test Japanese characters for readability against table row heights.

Survey the entire UI to make sure that you’re aware of all the places where copy will have to be translated. Create and maintain a spreadsheet as a catalogue of all text elements in your UI. This will help you cover your bases, and your development team can feed your catalogue into the resource library they will have to build.

## 4: Acknowledge your users

When you write context stories or examples of a user performing a task to show how a process works, consider the breadth of people who comprise the user base.

- Use names and characters that represent the range of our users.
- Avoid gender specificity where you can.
- If you use an acronym, provide the full name in a tooltip, so newer users don't have to stop and hunt up a term in the docs.
- Learn how users talk about their workflows, so you can avoid overly elaborate or stilted sounded copy. Use product jargon in cases where users are more likely to use it themselves.

---

## Checklists for writing and reviewing copy

**Write**

- [ ] Describe the product about which you’re writing: for example, “this is a software product that helps students find available financial aid for college”.
- [ ] Describe the purpose of this piece of work: for example, “this is a wizard for the student’s parents to use to provide all their relevant financial data to the aid committee”.

**Review**

- [ ] Does the page header tell the user what the page’s content includes?
- [ ] If you read the page’s sub-headers as a list, do they clearly describe all the content options on the page?
- [ ] Read your link text out loud. Where do you expect each link to take you?
- [ ] Read any image alt tags. What do they tell you about the image?
- [ ] Do form labels describe the field below them?
- [ ] Are form hints persistent and placed either above or below the fields?

---

## Further reading

- “A Web for Everyone” by Sara Horton and Whitney Quesenbery
- “Forms That Work” by Caroline Jarrett and Gerry Gaffney
- “Technically Wrong” by Sara Wachter-Boettcher
- [US General Services Administration Plain Language Guides](https://www.plainlanguage.gov/examples/)
- [Center for Plain Language](https://centerforplainlanguage.org/)
- [Aerospace and Defense Industry: Guide to Simplified Technical English](http://www.asd-ste100.org/)
- [Fonts Don’t Matter (Increasing Readability for Dyslexics)](https://axesslab.com/fonts-dont-matter/)
- [Accessibility Visualization Toolkit](http://khan.github.io/tota11y/)
- [Text Expansion and Contraction Chart](http://www.aranchodoc.com/wp-content/uploads/2017/07/Text-Expansion-Contraction-Chart3.png)
- [Sonnification Demo: Accessible Charts and Graphs](https://blogs.sas.com/content/sascom/2017/02/22/getting-started-sas-graphics-accelerator/)
