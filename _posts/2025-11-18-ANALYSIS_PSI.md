---
title: XAS Analysis (Paul Scherrer Institut Data)
date: 2025-11-18 20:00:00 +/-TTTT
categories: [Software Development, X-ray Spectroscopy]
tags: [PSI, XAS]     # TAG names should always be lowercase
author: manuel                    # for single entry
description: Python code for XAS data obtained at the cSAXS beamline of the Swiss Light Source (Paul Scherrer Institut, Villigen, Switzerland).
toc: True
math: true
---

## About the Project

This project contains the code used to obtain XAS spectra and Helical Dichroism (HD) signals from measurements acquired at the cSAXS beamline of the Swiss Light Source (Paul Scherrer Institut, Villigen, Switzerland). The input data are provided in HDF5 files and are processed entirely using Python.
The repository includes the class developed for reading the data and computing the XAS spectra and HD signals, as well as two Jupyter Notebooks: one demonstrating how to use the class to extract the XAS spectra and HD signals, and another showing the hierarchical structure of the HDF5 input files used for the analysis.

You can check the repository here: [XAS PSI GitHub Repo](https://github.com/Spoksonat/PhD_Project_1).