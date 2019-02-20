# DNA extractions lab notes

## Round 1

Samples 1-24. Low yield (ng)

### Protocol (w/ notes):**

1. 20 µL Proteinase-K in each tube

2. 10 µL blood / lysis buffer mix into each tube

*difficult to cleanly pipette; viscous texture. some samples get more, some less*

3. 190 µL Extraction Buffer into each tube ([via MacManes protocol](https://doi.org/10.6084/m9.figshare.658946.v1))

4. 200 µL lysis buffer (AL) into each tube

5. 200 µL 100% EtOH into each tube

6. 10 min incubation at 56°C (in heated vortex plate)

7. Pipette all contents to Qiagen spin column

8. Centrifuge 1 min @ 8000 rpm, discard waste, add to new colleciton tube

9. Add 500 µL Qiagen AW1 wash buffer to each tube

10. Centrifuge 1 min @ 8000 rpm, discard waste, add to new collection tube

11. Add 500 µL Qiagen AW2 wash buffer to each tube

12. Centrifuge 3 min @ 14000 rpm, discard waste, add to final microcentrifuge tube

13. Add 100 µL Qiagen AE elution buffer to each tube

14. Centrifuge 1 min @ 8000 rpm

15. Add 100 µL Qiagen AE elution buffer to each tube (second time)

16. Centrifuge 1 min @ 8000 rpm

### Qubit HS results

Used 2 µL sample. Forgot to vortex samples, so likely artifically low yield. Output in ng/mL, based off 10 µL of sample (which is incorrect). 

```
PNG048  3.85
PNG065  5.56
PNG073	4.14
PNG138	5.94
PNG038	8.03
PNG039	13.2
PNG040	9.02
PNG041	9.36
PNG063	5.66
PNG115	1.82
PNG116	3.6
PNG131	1.57
PNG136	3.66
PNG142	2.54
PNG114	3.1
PNG124	1.8
PNG140	5.35
PNG141	3.12
PNG143	1.48
PNG104	2.98
PNG121	2.95
PNG122	4.14
PNG123	4.93
```

## Round 2

Samples 1 -2 

### Protocol (w/ notes):

Same as above, except:

2. 20 µL blood / lysis buffer mix into each tube

*still difficult to cleanly pipette due to viscous texture. however, more even volumes for each tube*

16. Centrifuge 1 min @ 8000 rpm

*some fluid contact w/ base of spin column, didn't happen last time. uneven pipetting?*

### Qubit HS results

Used 2 µL sample. Accurately calibrated this time, results in ng/µL:

```
PNG048	27.2
PNG065	40.8
```

## Round 3

Same as protocol 2 above, but 56°C vortex plate for 15 min, 300 rpm gentle shake

*largely accurate pipetting, still viscous*

### Qubit HS results

Used 2 µL per sample. 

*Still incredibly low while being precise / showing little variance*

```
PNG048  2.94
PNG065  5.13
PNG073  3.47
PNG138	3.7
PNG038  3.67
PNG039  2.83
PNG040  7.14
PNG041  3.43
PNG063  2.95
PNG115  3.51
PNG116  1.31
PNG131  1.75
PNG136  1.32
PNG142  2.99
PNG114  3.59
PNG124  3.27
PNG140  1.63
PNG141  2.96
PNG143  1.93
PNG104  3.02
PNG121  1.94
PNG122  2.96
PNG123  2.66
PNG126  1.61
PNG128  1.6
```

*Per Kevin, this suggests an error with HS from too much DNA -- says I should use broad range (BR)*

Testing Qubit BR with `PNG048`,`PNG065`,`PNG073` and `PNG138`, 2 µL per sample. 

```
10.1
19.9
12.3
12.6
Standard 2 = ~480 (forgot to note this, suggests too-low values)
```


