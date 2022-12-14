# Addon Vehicle Loader

This resource finds all the vehicles by their folder name, processes the name and adds vehicle names to the game.

CFX.re forum link: https://forum.cfx.re/t/addon-vehicle-loader/4954197

## Usage
An example name for the resource folder would be `vehicle-loader`
Folder syntax: `brand-model_name`
Example: `apollo-intensa_emozione`

You should create one folder for the `.meta` (the files that set the vehicle's properties) files and another with the exact same syntax inside the stream folder, where you will store your `.yft` and `.ytd` files.
This resource needs to find the `.yft` file in order to get the game name.
The server script will take care of everything. You just need to create the folders with the correct syntax and put the relevant files in.

![Folder Structure](https://user-images.githubusercontent.com/1616657/203375188-984dc3cb-1045-4be8-aa5f-273678dd3f8c.png)

<sub>Download the release package. This is just the source.</sub>
