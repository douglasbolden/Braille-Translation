# Braille-Translation
Google Foobar Challenge code.

This application is a take on a Braille translator that involves the translation of letters, and spaces only, which
is part of the google challenge:

Because Commander Lambda is an equal-opportunity despot, she has several visually-impaired minions. But she never
bothered to follow intergalactic standards for workplace accommodations, so those minions have a hard time navigating
her space station. You figure printing out Braille signs will help them, and – since you’ll be promoting efficiency at
the same time – increase your chances of a promotion. Braille is a writing system used to read by touch instead of by
sight. Each character is composed of 6 dots in a 2×3 grid, where each dot can either be a bump or be flat (no bump).
You plan to translate the signs around the space station to Braille so that the minions under Commander Lambda’s
command can feel the bumps on the signs and “read” the text with their touch. 

Write a function answer(plaintext) that takes a string parameter and returns a string of 1’s and 0’s representing
the bumps and absence of bumps in the input string. Your function should be able to encode the 26 lowercase letters,
handle capital letters by adding a Braille capitalization mark before that character, and use a blank character
(000000) for spaces. All signs on the space station are less than fifty characters long and use only letters
and spaces.
