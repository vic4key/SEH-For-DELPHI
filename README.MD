### Manually implement SEH for DELPHI ###
_ _ _

This is the [Structured Exception Handling a.k.a SEH](https://en.wikipedia.org/wiki/Microsoft-specific_exception_handling_mechanisms#Structured_Exception_Handling) that I manually implemented in [Delphi](https://en.wikipedia.org/wiki/Delphi_(software)).

I used this SEH to avoid [BSOD](https://en.wikipedia.org/wiki/Blue_screen_of_death) in many kernel driver projects.

##### USAGE #####

```
uses VICSEH;

{$I VIC.TRY}
// YOUR CODE HERE THAT WANT TO TRY CATCH EXCEPTION HERE
{$I VIC.EXCEPT}
```
_ _ _

Website: https://vic.onl/
