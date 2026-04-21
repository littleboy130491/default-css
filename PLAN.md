user only need to change settings.css
tokens.css -> utility style default
layout.css, typography.css, components.css, and base.css -> the default setting from our system, hopefully it's good enough as fundamental

settings.css -> like the setting page where user assign the style. give the characteristics for each project.

user typically only need to change settings.css:
- set token css on element level: example: H1, H2, etc
- set token css on basic layout and spacing, ex: section width, container padding, etc
- set token css on basic components like button, cards, etc

then user might extend it for each elements or additional class, whether using tailwind or reguler css.

project.css -> user should add more custom css here for project-specific classes, overrides, and extra components.