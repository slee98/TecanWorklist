# Genterate Tecan Worklist

1. Get the initial DNA/RNA concentration from raw data measured by nanodrop 
2. Calculate the transfer of sample and diluent to achieve the target concentraiton
3. Generate the tecan worklist based on the calculation

#Tecan Worklist Format
A;PlateType;Position;Volume;LiquidClass;TipType;
A;PlateType;Position;Volume;LiquidClass;TipType;

Tip Code 
First Channel: 1
Second Channel: 2
Third Channel: 4
Fourth Channel: 8
Fifth Channel: 16
Sixth Channel: 32
Seventh Channel: 64
Eight Channel: 128


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

