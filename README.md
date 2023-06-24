# Generate Tecan Worklist

1. Get the initial DNA/RNA concentration from raw data measured by nanodrop 
2. Calculate the transfer of sample and diluent to achieve the target concentraiton
3. Generate the tecan worklist based on the calculation

# Tecan Worklist Format
- A;PlateType;Position;Volume;LiquidClass;TipType;
- A;PlateType;Position;Volume;LiquidClass;TipType;

Tip Code 
1. Channel: 1
2. Channel: 2
3. Channel: 4
4. Channel: 8
5. Channel: 16
6. Channel: 32
7. Channel: 64
8. Channel: 128


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

