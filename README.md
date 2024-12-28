# Harmony

Harmony is python Jupyter notebook showing correlation between music notes...

### Python modules

- matplotlib
- numpy

#### First cell

- Shows that notes are aranged in exponential order

#### Second cell

- Defines functions for making composition of two notes
- Plots base sine wave and iteraing over octave combination of base wave and wave with offset from 1 to 12 (12 for octave)
- Calculates imperfect period for combined waves
- **Score of period represents how far imperfect period is from perfect (Higher score means that signal is farther from being periodical)**
- More complex signal have higher count of base period, but it is harder for complex signal to achieve low period score
- Combination of notes sounds harmonical if period score is low

#### Second cell

- Makes major chord and minor chord wave
- Test period and period score of major and minor score
- Major score is lower than minor and period count is lower
- Hypothesis: Major chords have softer sound than minor and tend to be described as "happy" chord oposed to minor because of lower period score and period count
