# AnalogClock
HTML and CSS templates

Time into degrees
let hrPosition = (hr * 360) / 12 + (min * (360 / 60)) / 12 + 3 / 360;
let minPosition = (min * 360) / 60 + (sec * (360 / 60)) / 60 + 6 / 60;
let secPosition = (sec * 360) / 60 + 6;
