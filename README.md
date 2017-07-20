# Ergonomic Password Generator (EP)

```diff
- Even though the original paper claims that the ergonomic password scheme is secure, this might not be the case. Use at your own 
- risk. We found some statistical issues indicating that the security might not be as high as claimed by the authors. 
```

This is EP a small ergonomic password generator, written in JavaScript using the “window.crypto” browser API. Besides ergonomic passwords EP can generate normal passwords as well, the used charset can be configured.
Implementation by Simon Hanisch, based on [“Reduktion von Fehlerraten mittels ergonomischer Passwörter”](http://www.hochschule-trier.de/fileadmin/users/229/DACH_Herres_Weich-1.8.pdf) by Weich , Herres and Knorr.

