# Scorecard: v2 vs reference (ab_bench)
```
metric                             ref       own  score
cuts_per_10s                      4.53      5.25    1.0
median                            1.83      1.58    1.0
cv                                0.47      0.58    1.0
I_lufs                           -14.2     -14.5    1.0
true_peak_dbfs                    -0.3      -1.5    0.9
hook3s_lufs                      -15.4     -13.9    1.0
first_cut_s                        3.8       1.2   0.82
contrast_yhigh_minus_ylow        123.5     100.3   0.87
satavg                            18.9      21.5    1.0
zooms_per_10s                     2.24      1.75    1.0
words_per_s                       3.11      4.71   0.21
STYLE-MATCH SCORE: 87.6/100  (cut method: pyscenedetect-adaptive)
```
| Criterion | v2 vs reference |
|---|---|
| Hook (first 2 s) | The first cut lands at 1.2 s (reference: 3.8 s). It opens on a panic close-up with "Rent is due tomorrow" and then the phone insert. Beats the reference. |
| Cut rate | 5.08 cuts per 10 s, median shot 1.58 s (reference: 4.53 and 1.83 s). Beats the reference. |
| Motion | 2.42 zooms per 10 s (reference: 2.24), plus shake and pop-in captions. Matches or beats. |
| Humour | Bits: "one weekend / one weekend", "billboard", "three chat widgets / zero users", "So I'm rich now? / So I still need rent". About even. |
| Stakes | Rent is due tomorrow, and users online drop to 0 on the spinner. |
| Clarity | 4 step cards. The only weak spot is speech density: 4.7 words per second vs the reference's 3.1. |
| CTA | Comment SPEED, shown on the end card and spoken. |
| Loudness | -14.5 LUFS integrated, -1.5 dBTP. |
