---
title       : Mapping San Francisco Crime
subtitle    : A Shiny App
author      : Stephanie Roark
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

<style>
.title-slide {
  background-color: #EEEB7D;
}
</style>

## Mapping Crime in San Francisco

### - The SF Crime App displays a map of San Francisco with a crime heat map overalyed.


### - The App gives the user a view of the most common locations for each category of crime in San Francisco.


### - After choosing a category, the app generates a map of the location of each type of crime.

---

## Compare geographical distribution between sixteen crime categories

<div class='left' style='float:left;width:48%'>
- Arson<br/> 
- Assault<br/>
- Bribery<br/>
- Burglary<br/> 
- Driving Under the Influence<br/>
- Drug/Narcotic<br/>
- Embezzlement<br/>
- Extortion
</div>    
<div class='right' style='float:right;width:48%'>
- Fraud<br/>
- Gambling<br/>
- Larceny/Theft<br/>
- Prostitution<br/>
- Robbery<br/>
- Sex Offenses<br/>
- Suicide<br/>
- Vehicle Theft
</div>

---

## Example of how crime locations differs by category

Here are the maps for where Arson and Prostituion arrests occur most often.


<img src="assets/fig/unnamed-chunk-2-1.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />


---

## The San Francisco Crime App can help to keep us safe

### - Being aware of the most common locations for crimes to occur can allow a visitor to San Francisco to safely enjoy the city to the fullest.

### - The SF Crime App allows users to look for the crime hot spots in the city.

### - Examining the crime heat maps can also show trends in the different types of crimes occuring around the city.
