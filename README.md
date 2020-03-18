# Roulette Project

Using C#

This project is a console based Roulette game

## How to initialise
- Download - https://dotnet.microsoft.com/download
- If using VS Code, download the C# extensions 

## Areas of improvements
This is the initial game so it is a very basic version of Roulette, there are additions that can be added
    - Adding balances and limits on spending.
    - 

## Walkthrough
- Initially the game will welcome you and ask you to input your name
- Then the user will be asked whether they would like to make a bet on Numbers, Red/Black or Odd/Even
- If the user picks Numbers:
    - The user will be asked how much they are betting
    - They will be asked how many numbers they would like to bet on between 1-4. Odds are different depending on how many numbers they choose - 1 numbers 35/1, 2 numbers 17/1, 3 numbers 11/1 and 4 numbers 8/1. Once they have inputted their numbers the console will generate a random number, if the number matches what they have chosen then they will have won. The console then calculates their win dependant on the odds. 
- If the user picks Red/Black:
    - The user will be asked how much they are betting
    - They then choose if they are betting on Red or Black
    - The console then randomly generates either Red or Black
    - If the user picked correctly then their stake is doubled
- If the user picks Odd/Even:
    - The user will be asked how much they are betting
    - They then choose if they are betting on Odd or Even
    - The console then randomly generates a number
    - If the user picked correctly then their stake is doubled
