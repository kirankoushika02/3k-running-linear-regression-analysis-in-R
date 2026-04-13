# Inference and Linear Regression Analysis for 3 km Running Performance

## Overview
This project investigates 3 km running performance in a sample of well-trained male middle- and long-distance runners using statistical inference and simple linear regression. The analysis focuses on whether the population mean 3 km running time differs from 10.2 minutes, estimating confidence and tolerance intervals, and examining whether 3 km running time can be predicted from running velocity at a blood lactate concentration of 4 mmol/L (`v4mM`). :contentReference[oaicite:0]{index=0}

## Study Description
The dataset contains laboratory and performance measurements from sixteen well-trained male runners. Each athlete completed a 3 km time trial and several treadmill-based physiological tests, including:
- Running time over 3 km (`Running.Time`)
- Running velocity at blood lactate concentration of 4 mmol/L (`v4mM`)
- Running velocity at lactate threshold (`vTlac`)
- Relative oxygen uptake at 14.5 km/hr and 16.1 km/hr
- VO2 max related measurements :contentReference[oaicite:1]{index=1}

## Objectives
- Test whether the mean 3 km running time differs from 10.2 minutes
- Estimate a 95% confidence interval for the true population mean
- Estimate a tolerance interval for population running times
- Use simple linear regression to predict `Running.Time` from `v4mM`
- Interpret the strength and direction of the relationship between performance and physiological testing

## Tools and Libraries
- R
- tidyverse
- infer
- tolerance
- ggplot2
