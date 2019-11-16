#!/bin/bash                                                                                               
# Name: M************V*******R*******                                                                             
# Date: November 15, 2019                                                                                 
# File: timeod.sh                                                                                         
# Week: 4, Conditional Statements                                                                         
# Usage: Displays the time of day in a.m. or p.m. notation                                                
#        rather than in 24-hour clock time.                                                               

hour=$(date +"%H")
min=$(date +"%M")
sec=$(date +"%S")
current_date=$(date +"%A, %B %d, %Y")

echo

if [ "$hour" -gt 12 ]
then
    echo "$current_date" $(expr "$hour" - 12):"$min":"$sec" pm
elif [ "$hour" ==  0 ]
then
    echo "$current_date" 12:"$min":"$sec" pm
else
    echo "$current_date" "$hour":"$min":"$sec" am
fi
