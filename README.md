# Expo AsyncStorage Data Size Limit Exceeded

This repository demonstrates a common error in Expo applications: exceeding AsyncStorage's storage limit when working with substantial amounts of data. AsyncStorage, while convenient, has limitations.  This example showcases the problem and provides a solution by migrating to MMKV, a more robust and performant key-value storage option.

## Problem

Attempting to store large datasets within AsyncStorage results in an error.  The application might crash or exhibit unexpected behavior.

## Solution

The solution involves migrating to a more scalable storage mechanism like MMKV. MMKV offers significantly improved performance and storage capacity compared to AsyncStorage.  This example provides a clear demonstration of the migration process.

## Setup

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Follow the instructions in the `bugSolution.js` file for the updated implementation using MMKV.