---
title: "README.md"
author: "Steven Balogh"
date: "Tuesday, August 26, 2014"
output: pdf_document
---

bizd(date1=Sys.Date(),date2,formatz="%Y/%m/%d")
bizd is an R script function that calculates the number of business days between two dates. 

It accepts two dates and a format for those dates as arguments. The first date defaults to the current date and the format defualts to year/month/day.

It works by calculating the sequence of dates between the two dates in question, extracting all of the mon-fri dates, and eliminates any dates that appear in cal.

cal is a vector containing all 9 full-day trading holidays (new years, MLK day, President's Day, Good Friday, Memorial day,Independence day, labor day, Thanksgivign day, and Christmas Day) starting in 2014 through to 2070.

This script is under no copyright is amateurely licensed under GNU.
