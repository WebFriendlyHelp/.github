# Accessibility

Web Friendly Help LLC is an assistive technology business for blind and low-vision people, and I'm a blind developer. Everything in this organization gets built and used with a screen reader every day, so accessibility is not a feature added at the end. If a project here does not work with your screen reader, your keyboard, or your display settings, that is a bug.

Some repositories have their own ACCESSIBILITY.md with details for that project. This file is the default for any repository that does not.

## What I aim for

- Every feature works from the keyboard alone. Nothing requires a mouse or dragging.
- Screen reader output is correct and not noisy. NVDA and JAWS are what I use daily; Narrator gets checked too.
- Programs follow the font size, colors, and high contrast settings you chose in Windows rather than overriding them.
- Web pages and documents meet WCAG 2.2 AA. For desktop programs I use WCAG 2.2 AA as the bar where its criteria apply.

None of that is a formal certification. It is what I test against and what I fix when it falls short.

## Reporting a barrier

If something gets in your way, please tell me. Either route is fine:

- Open an issue on the repository the problem is in. Say which screen reader or other assistive technology you use and its version, what you were trying to do, and what happened instead.
- Or email help@webfriendlyhelp.com if you would rather not post publicly.

This is a one-person shop, but accessibility reports go to the front of the line.

## Contributing

If you send a change, keep it keyboard-operable and screen reader correct. A pull request that breaks either one will be asked to fix it before it is merged, no matter what else it improves.
