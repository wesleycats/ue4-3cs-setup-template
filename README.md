# Unreal Engine 4 Game Development Setup Template
*Unreal Engine 4.27 project template to quickly setup 3Cs*

This project's goal is to provide an easy-to-use & -edit 3rd Person Template for rapidly prototyping 3Cs containing the following features:
- Simple Save & Load System : **Not implemented**
- Dynamic Input Mapping System working with the UE plugin "Enhanced Input", with remapping functionality and UI : **Implemented**
- Dynamic Camera Setup System : **Not implemented**


# Dynamic Input Mapping System Setup Guide

![plugin-image](/guide/enhanced_input_remapping_system/2-plugin.jpg)
######1. Enable the plugin


![asset-creation-image](/guide/enhanced_input_remapping_system/3-asset-creation.jpg)
######2a. Create the enhanced input assets


![asset-creation-image](/guide/enhanced_input_remapping_system/4-assets-setup.jpg)
######2b. Setup the enhanced input assets


######3a. Create a character blueprint


![asset-creation-image](/guide/enhanced_input_remapping_system/5-bp-setup.jpg)
######3b. Setup a blueprint with the enhanced input nodes in the character blueprint


![asset-creation-image](/guide/enhanced_input_remapping_system/6-key-remapping-logic.jpg)
######3c. Setup a function with the key remapping logic in the character blueprint


![asset-creation-image](/guide/enhanced_input_remapping_system/7-key-remapping-setup.jpg)
######3d. Setup a call function for key remapping in the character blueprint


![asset-creation-image](/guide/enhanced_input_remapping_system/8-trigger-key-remapping.jpg)
######4. Setup trigger logic that can call the key remapping function
