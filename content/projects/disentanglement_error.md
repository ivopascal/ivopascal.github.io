---
date: '2025-08-10T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Disentanglement Error library'
draft: false # set to "true" if you want to hide the content 

link: "" # optional URL to link the logo to
params:
    button:
        icon: "icon-arrow-right"
        btnText: "Github Repo"
        URL: "https://github.com/ivopascal/disentanglement_error"
    image:
        src: "images/projects/disentanglement_error.png"
        scale: 0.3
    

## The content is used for the description of the project
---

There are two reasons why Machine Learning models can make mistakes. Either the task is noisy, so it's impossible to always be correct (aleatoric uncertainty), or the model has not learned everything yet (epistemic uncertainty).

We have had ways to estimate both of these for a while (for Neural Networks since 2017), but we did not have ways to evaluate whether these estimations were actually good. 

The Disentanglement Error allows you to measure whether these two kinds of uncertainty are estimated independetly. When one of the uncertainties change, it should not affect the other. This is an important property of disentangled uncertainties.