# Recipe Page Style Guide

## Fonts

- **Primary font:** `Outfit`, sans-serif (variable font weight 100–900)  
- **Heading font:** `Young Serif`, serif  
- **Font sizes:**  
  - Title (`.recipe__title`): 2.5rem  
  - Section titles (`.recipe__section-title`): 1.8rem  
  - Paragraphs and descriptions (`.recipe__description`): 1rem  
  - Ingredients (`.recipe__ingredient`): 1rem  
- **Font weights:**  
  - Titles: 500  
  - Ingredients: 600  
  - Descriptions: 500  
  - Nutrition labels: 500  
  - Nutrition values: 600  

## Colors

| Variable        | HSL Value           | Usage                          |
|-----------------|---------------------|--------------------------------|
| `--white`       | hsl(0, 0%, 100%)    | Backgrounds, containers        |
| `--stone-100`   | hsl(30, 50%, 90%)   | Section borders, light text    |
| `--stone-150`   | hsl(20, 1%, 47%)    | Secondary text, ingredients    |
| `--stone-600`   | hsl(30, 10%, 34%)   | Nutrition values, main text    |
| `--stone-900`   | hsl(24, 5%, 18%)    | Titles, main headings          |
| `--brown-800`   | hsl(14, 45%, 36%)   | Section headings               |
| `--rose-50`     | hsl(330, 100%, 98%) | Preparation time background    |
| `--rose-800`    | hsl(332, 51%, 32%)  | Accent colors (if any)         |

## Layout & Spacing

- Container max-width: 700px, centered horizontally  
- Padding inside containers: 25px (desktop), reduced on smaller screens  
- Section spacing:  
  - Section titles have margin-top: 2rem and margin-bottom: 1rem  
  - Paragraphs and lists have margin 1rem 0 or 0.5rem depending on context  

## Borders & Effects

- Sections separated by `border-bottom: 2px solid var(--stone-100)`  
- Nutrition table rows have `border-bottom: 1px solid #e5e7eb`, except last row  
- Border radius: 0.8rem for containers and images, smaller on mobile  

## Responsive Design

- At max-width 600px:  
  - Reduce font sizes for titles and text  
  - Reduce padding on containers and lists  
  - Make images slightly less rounded  

## Accessibility

- All images have descriptive `alt` attributes  
- Strong tags (`<strong>`) used for emphasis instead of `<b>`  
- Use semantic HTML5 elements (`<section>`, `<main>`, `<footer>`)  
- Ensure sufficient color contrast between text and backgrounds  

## Typography

- Use letter-spacing: 1px for titles and headings for readability  
- Line height default: 1.6 for paragraphs and body text  

---

*Created by Islomxon*  
*Challenge by [Frontend Mentor](https://www.frontendmentor.io?ref=challenge)*
