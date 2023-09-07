# Table of Contents

- [How many way can we use Tailwind?](#how-many-way-can-we-use-tailwind)
- [How Tailwind works](#how-tailwind-works)
- [Example of Tailwind classes](#example-of-tailwind-classes)
- [step by step learning flow with tailwind](#step-by-step-learning-flow-with-tailwind)

# How many way can we use Tailwind?

1. using play cdn(direct use)

- set within head tag: <script src="https://cdn.tailwindcss.com"></script>
- Tailwind CSS IntelliSense: In order for the extension to activate you must have tailwindcss installed and a Tailwind config file named tailwind.config.{js,cjs,mjs,ts} in your workspace.

# How Tailwind works

1. It will remove html native condition like there will be no difference between h1 vs p tag after apply Tailwind(do neutralize tags)

# Example of Tailwind classes

1. Text color

- text-slate-300 or text-[red] or text-[#50d71e]

2. Background

- color: bg-purple-400 or bg-cyan-500 hover:bg-cyan-600 or bg-[blue]
- Background-size: bg-auto or bg-cover or bg-contain
- Background-position:bg-center or bg-left-bottom
- Background-Image: bg-gradient-to-r from-purple-500 to-pink-500 or
  bg-[url('/img/hero-pattern.svg')]
- background-attachment: bg-fixed bg-local bg-scroll
  or bg-gradient-to-r from-green-400 to-blue-500 hover:from-pink-500 hover:to-yellow-500
- Gradient Color Stops: bg-gradient-to-r from-cyan-500 to-blue-500

3. Font family

- font-sans or font-serif or font-mono or font-sans hover:font-serif

4. font-size

- text-base(default-16px) or text-9xl(biggest-128px)

5. font-weight

- font-normal(default-font-weight: 400;) or font-black(biggest-font-weight:900)

6. Text Align

- text-center or text-start or text-end(text-align: left;)

7. Text Transform

- uppercase(text-transform: uppercase;) or capitalize

8. Borders

- Border Radius: rounded-full(circle-radius) or rounded-lg
- Border Width: border or border-2 or border-8 or border-x-2 or border-y-2
- Border color: border-red-300

9. Layout

- Z-Index: z-0 or z-20
- Position: relative or fixed or static(default) or sticky\
- Display: flex or grid or block or inline-block or hidden or table

10. Sizing

- width: w-96 or w-24 or w-1/2(half width) or w-full(full width) or w-max or w-fit or max-w-full
- height: h-96 or h-24 or h-1/2( half height) or h-full(full height) or h-fit

11. spacing

- Padding: p-2 px-2 py-2 ps-2 pe-2 pt-2 pr-2 pb-2 pl-2
- Margin: mb-2 like padding :Utilities for controlling an element's margin.
- Space Between: space-x-4(margin-left: 1rem;) or space-y-4(margin-top: 1rem;) Utilities for controlling the space between child elements.

12. Flexbox & Grid

- flex: flex or flex-1
- flex-direction: flex-col or flex-col-reverse
- justify-content: justify-center(justify-content: center;) or justify-start or justify-between
- Align Items: items-center( align-items: center;) or items-stretch
- grid: gird md:grid-cols-4 gap-2.5 or md:col-span-2 or row-span-2

13. Transitions & Animation
14. Transforms

- Rotate: rotate-45 or rotate-90

15. Interactivity

- cursor: cursor-pointer or cursor-progress or cursor-not-allowed or cursor-grabbing

16. Flex-Responsive

- flex: flex flex-col md:flex-row lg:justify-between

17. Grid-Responsive

- grid:
18. Effects
- Box Shadow Color: shadow-lg  shadow-indigo-500/50 or 

# step by step learning flow with tailwind

1. Getting started with tailwind, explore color
2. Tailwind Typography background, text, border
3. Explore Tailwind width, height, padding, margin
4. Tailwind Flex layout and responsive flex
5. Explore Grid layout and responsive grid
6. Penguin Fashion Project
