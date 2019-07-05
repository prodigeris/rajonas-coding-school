# Where is my delivery?

## Introduction

Your boss is extremely pleased with your team about that calculator you've recently made.
Using free intern labour saved him like 6 euros instead of purchasing them on Maxima. Success!

You silently sit at the desk, watching 9gag memes without doing any actual work, when out of nowhere the boss storms at your desk.

You had been preparing yourself for this exact moment for years and quickly alt-tab into Visual Studio Code in 0.32s.

**Boom!** A new Guinness world record.

The boss looks mad. 

"What? Did he see me switching the windows? It can't be possibly true!" you think to yourself.

You watch your boss closely, waiting for the worst but then he says, "I hate Barbora. Where is my goddamned delivery?"

"Umm... What?", you say confusedly.

"I just don't understand the customer service these days. I got the coordinates for my delivery. What am I going to do with them? I need your help!"

You feel relief and quickly agree to do this important task.


## Background

[You will be provided with some code boilerplate for handling user input.](../../boilerplate/where-is-my-delivery/index.html)

## Exercise

You're building an application that accepts coordinates from the user and tells the distance from the existing coordinates that you have.

Office coordinates are:

`54.89077, 23.919353`

Assign these coordinates to `officeLongitude` and `officeLatitude`.

Use the [distance formula](https://www.varsitytutors.com/hotmath/hotmath_help/topics/distance-formula) to calculate the difference between the coordinates, multiply by 100 and [round the result up](
).
This will represent a distance in kilometres.

Your application will have 2 prompts from the user:

1. Longitude
2. Latitude

These prompts will need to be assigned to variables called:

- `deliveryLongitude` (float)
- `deliveryLatitude` (float)

# Example

Assuming that the office location is `54.89077, 23.919353` (Kaunas),
when the user supplies the location of `54.687416,25.28004` (Vilnius), you would need to return: `138 km`

### Note

- Skipped prompts for coordinates will return `NaN`.
- This formula doesn't work on the Earth because the Earth is a sphere (or is it?). 
In a real-world scenario, you would have to use the [Haversine formula](https://en.wikipedia.org/wiki/Haversine_formula).