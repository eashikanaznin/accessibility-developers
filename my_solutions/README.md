# learnings

> ARIA used to make unaccessible components accessible
> WAI-ARIA With accessibility initiative by W3C
> ARI provides three attributes roll states and properties
> HTML > DOM Tree > Visual UI, JS can modify it > Accessibility tree > Assistive technology > User
> label Element: Used with form controls where The aria-label attribute is used to provide an accessible name for an element that may not have a visible label. 
> aria-lebelby: You win the level source is different
> aria-describeby:  used for additional descriptive text
> Roving focus : On the first element, if none of the option is checked Otherwise focus on the checked option
> aria-live can be set to off (not accessible by assistive tech), polite (won't interrupt), or assertive (will interrupt)
> hidden hides content from everyone, while aria-hidden hides content only from users relying on assistive technologies.
> display none and hidden, wont be accessed by assistive tech, takes no space in UI, cant be clicked or focused.
> opacity 0 , invisible but rendered, takes space, will be noticed by screen reader. 
> visibility hidden:  invisible but rendered, takes space, will NOT be noticed by screen reader.
> aria hidden, not noticed by Screen readers usually used with decorative items
> aria-live: Announces dynamic content changes to screen readers
> To maintain WCAG AA standard page font shoot adjust according to the zoom percentage
> Always avoid horizontal Scrolling when the pain is zoomed
> meta viewport tag Initial scale should be 1
> Always avoid using max-scale = 1 (prevents zooming) And user-scalable=no
> Use of grid , RM font size are recommended
> WCAG AA standard is using the contrast ratio of at least 4.5:1
> WCAG AA standard is using the contrast ratio of at least 7:1 (for text and images), 4.5:1 - for large texts
> Use colored extension to check the contrast ratios and then check in the contrast checker.
> touch target should be large enough
> Instead of fixed width, height use relative with, or percentage like 80%
> word-wrap, makes sure content remains in the area
> avoid overflow hidden, since it crops content and doesnt provide scrolling
> while using position absolute, provide a relative in the parent wrapper
> use of flex properties is remoccanded
