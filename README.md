# Birmingham-physics-year-2-lab-project-emission-spectra-of-noble-gases
This repository contains the code which Edward Penny and Emir Muhammad wrote to analyse data for the year 2 project emission spectra of noble gases

Due to the fact that we only started to keep copies of our old code approximently two third of the way through the term some of our earliest code is missing but the more recently writen code is has frequent versions showing gradual improvement.

We do not believe it is possible to upload files and add them to the branch of an existing file unfortunetaly. Instead we will upload all of the code seperatly and in this document we will write an overview of the changes between the document Spectra of Noble gases V11 condensed for git hub is the final version of our code.



Helium analysis data V0.1 
Is the earliest version of the code we have. It was written in approximently week 4 of labs. It imports all the data of a given ampule averages all images down to a graph of wavelength agaisnt intensity in arbetry units. It also plots vertical red lines on the graph showing the wavelengths detected which coniside with wavelengths of the true helium emission spectrum.

Spectra of Noble gases V1
Was writen in approximently week 5 of labs. It improves from the previous code by extending the averaging of the noble gases to all five of the noble gases rather than just helium. It also imports the true emission spectrums of the noble gases from an online source and converts them to multiple dictionaries which we can use to analyse our results.

Spectra of Noble gases V2
Was written in approximently week 5 of labs. The changes from V1 are that we wrote code which will detected the peaks of the emission spectrums using the functions find_peaks and peak_prominences. We have also writen code which will convert the measured emision spectrums into equations where each detected peak is representedby a gaussian.

Spectra of Noble gases V3
Was written in approximently week 6 of labs. This is an overall refienment of V2 simplifing the code in many places. It also contains so rough analysis of the compositionof the data. We also introduced a system that allowed two people to switch between using the code more easily by being able to change the locations the code looked for the data in more easily.

Spectra of Noble gases V4
Was written in approximently week 7 of labs. Improves on V3 by adding code which will scale the relative intensities we found in the online data for the emission spectrums of noble gases into comparable intensities which we could use for curve fitting. It also contains code which attempts to fit the true data to our measured data using the function curve_fit.

Spectra of Noble gases V5
Was written in week 8 of labs. It improves on V4 as it includes code which will scale all the true noble gas emission spectrums from relative intensities to comparable intensities.

Spectra of Noble gases V6
Was written in approximently week 8 of labs. The changes from V5 are an overall refinment of the code making it more readable and simpler to follow. We also began to start fitting our data using this code.

Spectra of Noble gases V7
Was written in week 9 of labs. Improvements from V6 are that the presentation of the final data is in a more understandble form. It has been scaled so that it is in the form of decimals which can easy be converted to percentages for the percentage composition of the ampules. The calculated errors are also included.

Spectra of Noble gases V8
Was written in week 9 of labs. Is a refinment of V7 removing unessary code. It also adds pie charts for the final data to all the results to be easily presented.

Spectra of Noble gases V9
Was written in week 9 of labs.Removes bugs and mistakes from V8 which had lead to the results being off slightly.

Spectra of Noble gases V10 final form
Was written in week 9 of labs. Fixes a mistake in V9 where there was no initial conditions selected for the curve fitting which lead to cery large errors on the final answer.

Spectra of Noble gases V11 reduced for git hub
Was written in week 9 of labs. It is a condensed version of V10 containing only the vitial code which we used to calculate our final data.
