# Sine-wave-generation-using-Matlab
```
   %%Time specifications:
   Fs = 100;                   % samples per second
   dt = 1/Fs;                   % seconds per sample
   StopTime = 0.25;             % seconds
   t = (0:dt:StopTime-dt)';     % seconds
   %%Sine wave:
   Fc = 60;                     
   x = cos(2*pi*Fc*t);
   % Plot the signal versus time:
   figure;
   plot(t,x);
   xlabel('time (in seconds)');
   title('Signal versus Time');
   zoom xon;

```
