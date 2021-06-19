# STR-food-menu-TH
Scene Text Recognition on Thai food menu image

![demo1](demo/demo1.png)

## Overview
This pro ________________ (table-like data) As the Text Localization model and Text Recognition model are private model, so they are not provided in this repository. However, I've provided all pipeline code and the behavior of the missing model function, hence you can put your models into the blank space in my code.


## Scope Of Work
- Dishname should be in the form of Thai text
- The content should be in the form of "Front + Dishname + Price + Back"
  - Front: 
  - Dishname
  - Price
  - Back
- Not only recognize the dish name and price but the model should also be able to pair them correctly

## Pipeline
- Preprocessing: ROI from user
- Text Localization: Private model
- Text Recognition: Private model
- Post Processing: Matching Algorithm

## Preprocessing

### Without ROI
![demo3_no_ROI](demo/demo3_no_ROI.png)

### With ROI
![demo3](demo/demo3.png)

## Text Localization

## Text Recognition

## Post Processing

## Demonstration
![demo2](demo/demo2.png)
![demo4](demo/demo4.png)
